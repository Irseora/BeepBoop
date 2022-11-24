- ILDASM - Intermediate Language DisAssembler
- Nivelul: limbaj masina / limbaj asamblare
- **Compilator** = limbaj inalt --> limbaj asamblare
	- independent de arh. --> dependent de arh.
- **Asamblor** = program scris --> limbaj asamblare --> cod binar exec.
- *Limbaje compilate*: C, Fortran
	- cod binar se exec. direct pe masina
- *Limbaje ?* : Java
	- JVM: masina virtuala java
		1. opreste translatarea la byte-code
		2. executa byte-code-ul
		- $\exists$ implementari hardware - byte-code exec. direct

#### Dimensiunile tipurilor de date
 | Nume        | Marime (bit) |
 | ----------- | ------------ |
 | Bit         | 1            |
 | Nibble      | 4            |
 | Byte        | 8            |
 | Half-Word   | 16 / 32           |
 | Word        | 32 / 64           |
 | Double-Word | 64 / 128           |
 | Quad-Word   | 128 / 256          |

---

### [[031 - ARC|ARC, A RISC Computer]]

---

### Pseudo-operatii

---

### Programe in Assembly

---

### Accesarea Datelor in Memorie - Moduri de Adresare
- LSB = Least Significant Byte
- MSB = Most Significant Byte
- Endian = terminatia

#### Big-Endian
- MSB --> LSB
- cuvantul se termina la adresa mare
- MSB - cea mai mica adresa

#### Little-Endian
- MSB <-- LSB
- cuvantul se termina la adresa mica
- LSB - cea mai mica adresa

---

### Legarea Subrutinelor

---

### In & Out in Assembly

---

### Studiu de Caz: ASI pentru Masina Virtuala Java