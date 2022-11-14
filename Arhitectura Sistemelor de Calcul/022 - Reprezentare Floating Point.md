- biti necesari pt. reprez. unui nr.: $log_2 \ (10 ^ {\text{nr. cifre din baza }10})$

### Numere in Baza 10
- compromisuri la precizie
- pct. dec. nu se stocheaza
- **Significand / Mantisa** = fractie
- **Precizia** = nr. de cifre din significand / mantisa
- **Plaja de valori** = nr. de cifre rezervate exponentului
- cel mai mare nr. (6 cifre): $9.999 \times 10^{99}$
- cel mai mic nr. (6 cifre): $-9.999 \times 10^{99}$
- total nr. reprez. exact (fara eroare / rotunjire): $2 \times 10^6 - 1$
	- -1 pt. ca sunt 2 reprez. ale lui 0
![[Pasted image 20221107031432.png]]

### Normalizare
- multitudinea reprez. => probleme la efectuarea comparatiilor
	$254 = 254 \times 10^0 = 25.4 \times 10^1 = 2.54 \times 10^2 = .254 \times 10^3 = .0254 \times 10^4 = ...$
- **Normalizare (standardizare)** = poz. pct. dec. este intotdeauna fixata pt. un anumit nr.
- de obicei, in stanga celei mai semnificative cifre: $.254 \ times 10^3$
- **Notatie stiintifica** = pct. dec. in partea dreapta a celei mai semnificative cifre: $1.1 \times 2^{-4}$

### Formatul IEEE-754
![[Pasted image 20221107032054.png]]

### Studiu de Caz: Rachetele Patriot
- esec, datorita pierderii preciziei
- operatiunea "Furtuna in desert" -> 1991 - 1992
- 25. Feb. 1991
- pierderea preciziei la conversie intreg 24 biti -> real 24 biti
  => esecul unui sistem anti-rachete Patriot (radar)
- 28 soldati americani morti
![[Pasted image 20221107032321.png]]