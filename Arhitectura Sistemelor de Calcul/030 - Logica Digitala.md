### Definitii
- **Logica combinationala** = decizii doar pe baza input-ului
- **Logica secventiala** = decizii pe baza input-ului & a unor date mai vechi
- **[[031 - Masini cu Numar Finit de Stari|Masini cu numar finit de stari]]** = output-uri in functia input-ului & a starii interne
  (ex. automat pt. vanzari)
- **Unitate combinationala logica** = traduce multimea input => multime output, conform uneia / mai multor functii
	- ![[Combinational Logic Unit.png]]
	- output depinde doar de input
- XOR = adunare % 2
- **Postulat** = adevar fundamental, care nu are nevoie de demonstratie
- **Contor de poarta** = masura a complexitatii unui circuit, nr. tututor portilor


### Tabele de Adevar
- *1854 - George Boole*
- output pt. fiecare input posibil

|$A$|$B$|$False$|$AND$|$A \bar B$|$A$|$\bar A B$|$B$|$XOR$|$OR$|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|0|0|0|0|0|0|0|0|0|0|
|0|1|0|0|0|0|1|1|1|1|
|1|0|0|0|1|1|0|0|1|1|
|1|1|0|1|0|1|0|1|0|1|

|$A$|$B$|$NOR$|$XNOR$|$\bar B$|$A + \bar B$|$\bar A$|$\bar A + B$|$NAND$|$True$|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|0|0|1|1|1|1|1|1|1|1|
|0|1|0|0|0|0|1|1|1|1|
|1|0|0|0|1|1|0|0|1|1|
|1|1|0|1|0|1|0|1|0|1|


### Porti Logice
```````col
``````col-md
##### AND
![[AND Gate.png]]
``````

``````col-md
##### OR
![[OR Gate.png]]
``````

``````col-md
##### Buffer
![[Buffer Gate.png]]
``````

``````col-md
##### NOT (Inverter)
![[NOT Gate.png]]
``````
```````
```````col
``````col-md
##### NAND
![[NAND Gate.png]]
``````

``````col-md
##### NOR
![[NOR Gate.png]]
``````

``````col-md
##### XOR
![[XOR Gate.png]]
``````

``````col-md
##### XNOR
![[XNOR Gate.png]]
``````
```````

### [[032 - Algebra Booleeana|Algebra Booleeana]]
![[032 - Algebra Booleeana#Definitii]]


### [[033 - Forma Suma de Produse|Forma Suma de Produse]] 
![[033 - Forma Suma de Produse#Definitie]]

### [[034 - Forma Produs de Sume|Forma Produs de Sume]]
![[034 - Forma Produs de Sume#Definitie]]


### [[035 - Componente Digitale|Componente Digitale]]
![[035 - Componente Digitale#Definitie]]
