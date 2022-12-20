- named & optional arguments: `Console.WriteLine(Convert.ToString(x, toBase: 2));`
- `PadLeft(32, '0')`
- `Console.WriteLine({...}, 32)` - total width dreapta (-32 stanga)
- ==Legarea subrutinelor==

---

###### Asamblor / Emulator ARC
- regex
- bitwise & shift operators (logic / arithmetic)
	- `>>>`, `<<<` always logic
- `uint`
- `byte` / `sbyte`
- `var` = compilatorul infereaza tipul de date

---

###### Extensii Tipuri de Date
```csharp
public static class Extension
{
	// Seteaza bitul dat (1)
	public static uint SetBit(this uint n, int offset)
	{
		uint mask = 1u << offset;  // unsigned constant
		n |= mask;
		
		return n;
	}
	
	// Reseteaza bitul dat (0)
	public static uint ResetBit(this uint n, int offset)
	{
		uint mask = -(1u << offset)
		n |= mask;
		
		return n;
	}

	public static uint GetBit(this uint n, int offset)
	{
		return (n >> offset) & 1u;
	}
}
```

---


### Curs

```
! Add 2 numbers
	   .begin        ! Pseudo-operatie
	   .org 2048     ! Adresa la care incepe programul
prog1: ld     [x], %r1       ! Load x in r1
	   ld     [y], %r2       ! Load y in %r2
	   addcc  %r1, %r2, %r3  ! %r3 = %r1 + %r2
	   st     %r3, [z]       ! Store %r3 in z
	   jmpl   %r15 + 4, %r0  ! Return
x:     15
y:     9
z:     0
       .end
```
- `[x]` - valoarea de la adresa `x`
- `jmpl %r15 + 4, %r0` - jump & link
	- `%r15` - adresa ultimei instructiuni inainte de subrutina (call)
	- `%r15 + 4` - adresa urmatoare dupa call

```
a_start   .equ 3000
...
...

loop: ...
      ...
      ba loop

done:     jmpl %r15 + 4, %r0

length:   20            ! 5 numbers = 20 bytes
address:  a_start
          .org a_start  ! Start of array a
a:        25
         -10
          33
          -5
           7
          .end
```

###### Asamblor
- fisier txt -> cod masina (secvente de 32 biti)

###### Masini cu 3 adrese
- $A = B \times C + D =$ `mult B, C, A` $\ \rightarrow$ `add D, A, A`
- Traficul in mem: $14+2 \times (2 \times 3) = 26$ octeti

==Moduri de adresare==

#### Legarea subrutinelor
- transmite parametrii prin registre
```
! Calling Routine
    ...
    ld   [x], %r1
    ld   [y], %r2
    call add_1
    st   %r3, [z]
    ...
x: 53
y: 10
z:  0

! Called routine: %r3 = %r1 + %r2
add_1: addcc %r1, %r2, %r3
       jmpl  %r15 + 4, %r0
```

##### Data Link Area
- zona legatura de date
- adresa zonei de memorie transmisa printr-un registru (`%r5`)
- `.dwb` = define word block
```
! Calling routine
...
st    %r1, [x]
st    %r2, [x+4]
sethi x, %r5
srl   %r5, 10, %r5
call  add_2         ! x[2] = x[0] + x[1]
ld    [x+8], %r3    ! %r3 = x[2]

! Data link area
x: .dwb 3

! Called routine: x[2] = x[0] + x[1]
add_2: ld    %r5, %r8          ! %r5 = x[0]
       ld    %r5 + 4, %r9      ! %r5 + 4 = x[1]
       addcc %r8, %r9, %r10
       st    %r10, %r5 + 8     ! %r5 + 8 = x[2]
       jmpl  %r15 + 4, %r0
```

##### Stiva
- stiva trebuie sa fie lafel la finalul apelarii ca inainte de apelare
```
! Calling routine
...
%sp .equ  %r14           ! #define %sp = %r14
    addcc %sp, -4, %sp   ! Scoate un element din stiva (sp--)
    st    %r1, %sp
    addcc %sp, -4, %sp
    st    %r2, %sp
    call  add_3
    ld    %sp, %r3
    addcc %sp, 4, %sp

! Called routine
%sp .equ %r14
add_3: ld    %sp, %r8
       addcc %sp, 4, %sp
       ld    %sp, %r9
       addcc %r8, %r9, %r10
       st    %r10, %sp
       jmpl  %r15 + 4, %r0   ! Readuce unde era inainte de apel
```