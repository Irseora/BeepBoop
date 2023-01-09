- **Filtru**: O submult. $F \ne \emptyset$ a lui $B$ (o algebra Boole), daca au loc: $\hspace{1cm} \forall x,y \in B$
	- $F_1: \ \ x,y \in F \ \Rightarrow \ x \land y \in F$
	- $F_2: \ \ x \in F, \ x \le y \ \Rightarrow \ y \in F$

- **Ideal**: O submult. $I \ne \emptyset$ a lui B (o algebra Boole), daca au loc: $\hspace{1cm} \forall x,y \in B$
	- $I_1: \ \ x,y \in I \ \Rightarrow \ x \lor y \in I$
	- $I_2: \ \ y \in I, \ x \le y \ \Rightarrow \ x \in I$

- *Observatii*: 
	- Notiunea de filtru & ideal sunt duale. 
	  Deci din $\forall$ prop. pt. filtre in algebre Boole, se pot obtine prop. ale idealelor, prin dualizare.
	- $\forall$ intersectie de filtre este filtru

==filtru generat==

- **Congruenta**: O rel. de echiv. $\sim$ pe $B$ (o algebra Boole), daca au loc: $\hspace{1cm} \forall x,y \in B$
	1. $x \sim y, \ x' \sim y' \ \Rightarrow \ x \lor x' \sim y \lor y'$
	2. $x \sim y, \ x' \sim y' \ \Rightarrow \ x \land x' \sim y \land y'$
	3. $x \sim y \ \Rightarrow \bar x \sim \bar y$

- **Corespondenta dintre filtre si congruenta**:
	- Vom stabili o corespondenta biunivoca
	- Unui filtru $F$ ii asociem relatia liniara: $x \sim_F y \ \Leftrightarrow \ \begin{cases} x \leftrightarrow y \in F \\ x \rightarrow y \in F \ \text{ si } \ y \rightarrow x \in F \end{cases}$
		- $\sim_F$ este o congruenta a lui $B$.
	- Reciproc, unei congruente $\sim$ ii asociem filtrul: $\tilde{F} = \{x \in B \ | \ x \sim 1\}$ a lui $B$
	- Din cele 2 $\Rightarrow$ mult. tuturor filtrelor a lui $B$ este in corespondenta biunivoca cu multimea congruentelor lui $B$

