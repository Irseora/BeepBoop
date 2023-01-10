###### Precizari
-  10-20 pagini
- trimitem inainte de examen
- lori_andrei@yahoo.com

---

### Axiome ale calculului propozitional
- formal basis of logic
- NOT, OR, AND, implies
- many different systems
- consistency, completeness, independece of axioms
- = sentential calculus
- Axioms
	1. $F \Rightarrow (G \Rightarrow F)$
	2. $(F \Rightarrow G) \Rightarrow ((F \Rightarrow (G \Rightarrow )) \Rightarrow (F \Rightarrow H))$
	3. $F \Rightarrow (G \Rightarrow F \land G)$
	4. $F \Rightarrow F \lor G$
	5. $F \Rightarrow G \lor F$
	6. $F \land G \Rightarrow F$
	7. $F \land G \Rightarrow G$
	8. $(F \Rightarrow G) \Rightarrow ((H \Rightarrow G) \Rightarrow (F \lor H \Rightarrow G))$
	9. $(F \Rightarrow G) \Rightarrow (F \Rightarrow \neg G) \Rightarrow \neg F)$
	10. $\neg \neg F \Rightarrow F$
- $F, H, G = \forall sentential formula$
- Rule of inference - Modus Ponens
	- $\displaystyle \frac{F,F \Rightarrow G}{G}$
		- if $F$ and $F \Rightarrow G$ are axioms / deduced from axioms through inference, then $G$ is also a formal theorem
	- $\Rightarrow$-elimination
- Deduction theorem: $\Rightarrow$-introduction

---

### Teorema deductiei
- Deduction = the process of drawing conclusions from premises & syllogisms
- metatheorem
- = conditional proof
- if $B$ can be derived from $A_1, ... , A_n$ then $A_n \Rightarrow B$ can be derived from $A_1, ..., A_{n-1}$
	- if thesis $S$ can be proven under hypotheses $U, V$, then $V$ implies $S$ under hypothesis $U$

---

### Algebra Lindenbaum - Tarski
- 

---

###### Sources
- Wolfram Alpha (Mathworld)
- Matematica: Manual pentru clasa a IX-a: Trunchi comun + curriculum diferentiat
- Course Notes

---

- conjecture / hypothesis = apparently true, but neither verified nor disproven
- axiom = proposition self-evidently true without proof
- axiom schema = sentential formula representing infinitely many axioms
	- ex: $F \Rightarrow F \lor G$
		- $A \Rightarrow A \lor B, \ \ A \Rightarrow A \lor A, \ \ \neg A \Rightarrow \neg A \lor B$
		- $(A \Rightarrow B) \Rightarrow (A \Rightarrow B) \lor (D \land E)$

---

### 1. Calculul propozitiilor (prezentare neformalizata)
#### 1.1. Propozitiile
Enunt, univers, subiect, predicat, propozitii (initiale/primitive $P_0$, compuse)
Conectori logici/propozitionali: $\neg, \lor, \land, \rightarrow, \leftrightarrow$
#### 1.2. Valoarea de adevar a unei propozitii
Functia de adevar/evaluare: $v_0 : P_0 \rightarrow \{0,1\}, \ \ v_0(p) = \begin{cases} 1, & p \ adevarat \\ 0, & p \ fals \end{cases}$
Tautologie, antilogie, ~, principiul generalizarii
**Axiome ale sistemului formal al calculului propozitiilor**
Limba, vocabular ($P_0$, conectori logici, paranteze), gramatica (R1-R3), totalitatea frazelor posibile ($P$)
Meta-limbaj, meta-meta-limbaj

### 2. Calculul predicatelor (prezentare neformalizata)
#### 2.1. Predicatele
Predicat, variabila libera
Mult. de obiecte/domeniul unui predicat, predicat partial, prop. complexe
Cuantificatori: $\exists, \forall$
Conventii de scriere
#### 2.2. Valoarea de adevar a unui predicat
Adevarat/fals/ambivalent
Lege logica, tautologie, tautologie cuantificata

### 3. Latici
#### 3.1. Multimi (pre)ordonate
Relatii de ordine (partiala)
Multime (partial) ordonata, multime total ordonata/liniara/lant, multime preordonata
##### 3.1.1. Principiul dualitatii. Diagrama Hasse
##### 3.1.2 Reprezentarea unei relatii binare pre o multime finita prin matrice booleana
##### 3.1.3. Prim (ultim) element, minorant (majorant), infimum (supremum). Axioma lui Zorn