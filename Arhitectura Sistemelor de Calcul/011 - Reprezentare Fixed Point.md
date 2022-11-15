- **Precizia** = distanta dintre 2 nr. succesive
- **Eroare maxima** = $\text{un nr. } \mathbb{R} - \text{cel mai apropiat } \mathbb{Z}$ = $\text{Precizie } / \ 2$
	- cu 2 cif. din baza 10 => $[-99, +99]$ => 199 nr.
		- Precizia: $11 - 10 = 1$
		- Eroarea maxima: $1 \times 1/2 = 0.5$
- in intervalul $[a,b]$ sunt $b-a+1$ nr.
- in intervalul $[a,b]$ se impart cu $k$  $[b/k]-[a/k]$ nr.

### Cod cu Ponderi ale Pozitiei + Conversie
- Valoarea zecimala a unui nr.:  $\sum ^{n-1} _{i=-m} b_i \times k^i$
	- k = baza
	- n = nr. cif. parte intreaga
	- m = nr. vif. parte fractionara
- $541.25_{10} = 5 \times 10^2 + 4 \times 10^1 + 1 \times 10^0 + 2 \times 10^{-1} + 5 \times 10^{-2} = 500 + 4 + 1 + 2/10 + 5/100$
- $202.22_4 = 2 \times 4^2 + 0 \times 4^1 + 2 \times 4^0 + 2 \times 2^{-1} + 2 \times 2^{-2} = 2 \times 16 + 2 + 2 \times 0.25 + 2 \times 0.125 = 34.625_{10}$

### Metoda Restului + Inmultirii
$23.375_{10} = 10111.011_2$
- Partea intreaga: $23_{10} = 10111_2$
	$23/2=11(1)$
	$11/2 = 5 (1)$
	$5/2 = 2 (1)$
	$2/2 = 1(0)$
	$1/2 = 0 (1)$
- Partea fractionara: $.375_{10} = 0.11_2$
	$.375 \times 2 = 0.75$
	$.75 \times 2 = 1.5$
	$.5 \times 2 = 1.0$

### Fractii Periodice in Baza 2
- **Fractie neperiodica**: numitorul este de forma $2^m \times 5^n$, unde m si n sunt $\ge$ 0  
- **Fractie periodica simpla**: numitorul nu se divide cu 2 si nici cu 5
- **Fractie periodica mixta**: numitorul se divide cu 2 si/sau 5 SI se mai divide si cu alte numere prime

### Bazele de Numeratie 2, 3, 8, 10, 16
|Binary (2)|Tertiary (3)|Octal (8)|Decimal (10)|Hexadecimal (16)|
|---|---|---|---|---|
|0|0|0|0|0|
|1|1|1|1|1|
|10|2|2|2|2|
|11|10|3|3|3|
|100|11|4|4|4|
|101|12|5|5|5|
|110|20|6|6|6|
|111|21|7|7|7|
|1000|22|10|8|8|
|1001|100|11|9|9|
|1010|101|12|10|A|
|1011|102|13|11|B|
|1100|110|14|12|C|
|1101|111|15|13|D|
|1110|112|16|14|E|
|1111|120|17|15|F|




### Baze Puteri ale lui 2
- $1011_2 = 10_2 \ 11_2 = 23_4$
- $23_4 = 2_4 \ 3_4 = 1011_2$
- $101010_2 = 101_2 \ 010_2 = 52_8$
	- grupe de cate 3, pt. ca $8 = 2^3$
- $01101101_2 = 0110_2 \ 1101_2 = 6D_{16}$

### Numere cu Semn
#### Magnitudine cu Semn
- bit de semn (0 = poz., 1 = neg.)
- $+25_{10} = 00011001_2 \hspace{1cm} -25_{10} = 10011001_2$
- $+0_{10} = 00000000_2 \hspace{1.25cm} -0_{10} = 10000000_2$

#### Complement fata de 1
- bit de semn (0 = poz., 1 = neg.)
- complementam restul bitilor (0 -> 1, 1 -> 0)
- $+25_{10} = 00011001_2 \hspace{1cm} -25_{10} = 11100110_2$
- $+0_{10} = 00000000_2 \hspace{1.25cm} -0_{10} = 11111111_2$

#### Complement fata de 2
- bit de semn (0 = poz., 1 = neg.)
- compl. fata de 1 + 1
- $+25_{10} = 00011001_2 \hspace{1cm} -25_{10} = 11100110_2 + 1_2 = 11100111_2$
- $0_{10} = 00000000_2$

#### Exces
- bit de semn (1 = poz., 0 = neg.)
- **Exces x** = adunam x la compl. fata de 2, ignorand carry out
- numerele mici folosesc mai putini biti => simplifica compararea
- $+12_{10} = 10001100_2 \hspace{1cm} -12_{10} = 01110100_2$
- $0_{10} = 10000000_2$

#### Reprezentari BCD
- Binary Coded Decimal
- in compl. fata de 9 & 10
- CON: folosim mai multi biti decat e nevoie
- fiecare cifra este formata din 4 biti
	- $0000 \hspace{3mm} 0011 \hspace{3mm} 0000 \hspace{3mm} 0001 \hspace{3mm} (+301)_{10} \text{ \ \ \ 9's \& 10's compl.}$
	$\hspace{0.8cm} 0_{10} \hspace{6mm} 3_{10} \hspace{6mm} 0_{10} \hspace{6mm} 1_{10}$
	- $1001 \hspace{3mm} 0110 \hspace{3mm} 1001 \hspace{3mm} 1000 \hspace{3mm} (-301)_{10} \text{ \ \ \ 9's compl.}$
	$\hspace{0.8cm} 9_{10} \hspace{6mm} 6_{10} \hspace{6mm} 9_{10} \hspace{6mm} 8_{10}$
	- $1001 \hspace{3mm} 0110 \hspace{3mm} 1001 \hspace{3mm} 1001 \hspace{3mm} (-301)_{10} \text{ \ \ \ 10's compl.}$
	$\hspace{0.8cm} 9_{10} \hspace{6mm} 6_{10} \hspace{6mm} 9_{10} \hspace{6mm} 9_{10}$