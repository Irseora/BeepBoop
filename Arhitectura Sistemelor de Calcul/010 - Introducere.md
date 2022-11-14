### Definitii
- **Arhitectura calculatoarelor** = comportamentul functional al calculatoarelor, vizibile programatorului
  (dim. tipurilor de date)
- **Organizarea calculatoarelor** = relatiile structurale, nu sunt vizibile programatorului
  (clock speed, dim. mem. fizice)

### Istorie
- *Masina de calcul a lui Pascal*   ->  sec. 17
	- operatii aritm. elementare
	- NU are comp. elementare ale unui calc.
- *Charles Babbage*  ->  sec. 19
	- model teoretic
	- control mecanic & calcule mecanice = comp. unui calc. digital
- *Enigma*
	- Siemens
	- masina de criptat, WWII
	- spart de *Alan Turing - Colossus*
- *ENIAC* = Electronic Numerical Integrator & Computer
	- J. W. Mauchly & J. P. Eckert - University of Pensilvania
	- primul calc. electronic, digital, capabil de reprogramat

### Modelul Von Neumann
![[Pasted image 20221107015729.png]]

### Modelul System Bus
- *Magistrala sistem* = cale de comunicare intre componente
- imbunatatire a modelului Von Neumann

![[Pasted image 20221107015750.png]]

### Niveluri ale Masinilor de Calcul
- sus -> baza: devin mai putin abstracte, structura interna devine vizibila
- **Compatibilitate "in sus"** = calc. mai puternice pot rula soft. facut pt. calc. mai slabe
- **Programe portabile** = prog. in limbaje inalte, pt ca pot fi recompilate

![[Pasted image 20221107015900.png]]

### Legea lui Gordon Moore
> Puterea de calcul (nr. tranzistori) se dubleaza la fiecare 18 luni, iar pretul ramane acelasi.

- fondatorul Intel
- trebuie tinut cont in planificarea proiectelor de anvergura
- peste cati ani vom avea procesoare de n ori mai puternice decat azi? $log_2 \ n \times 1.5$