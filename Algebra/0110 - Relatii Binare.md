- **Relatie binara** = sistem ordonat $\rho = (A, B, R)$
	- $\rho$ - numele relatiei
	- A - domeniu
	- B - codomeniu
	- R - grafic - $R \subseteq A \times B$
- **Relatie omogena**: $A = B$
	- Relatiile omogene pot fi:![[0111 - Reflexiv, Tranzitiv, Simetric, Antisimetric]]
- **Relatia totala**: $R = A \times A$
- **Relatia de egalitate / diagonala**: $R = \Delta_A = \{(a,a) \ | \ a \in A\}$, $\text{unde } a \Delta_A b \iff a = b$
	- Pentru $\rho = (A, B, R), \hspace{5mm} R \circ \Delta_A = \Delta_B \circ R = R$
- **Inversa relatiei**: $\rho ^{-1} = (B, A, R^{-1}), \hspace{5mm} R^{-1} = \{(b, a) \in B \times A \ | \ (a,b) \in R\}$
	- Inversa unei relatii NU este inversa in raport cu operatia de compunere
	  In general $R^{-1} \circ R \ne \Delta_A$ si $R \circ R^{-1} \ne \Delta_B$
	- Pentru $(A,B,R)$ si $(B,C,G), \hspace{5mm} (G \circ R)^{-1} = R^{-1} \circ G^{-1}$
- **Sectiunea rel. R dupa submultimea X**: $R(X) = \{y \in B \ | \ \exists x \in X \text{ a.i. } (x,y) \in R\}$
- **Sectiunea rel. R dupa elementul x**: $R<x> = \{y \in B \ | \ (x,y) \in R\}$

### Operatii cu Relatii
$\rho_1 = (A,B,R_1), \ \rho_2 = (A,B,R_2)$
- **Complementarea**: $\bar \rho = (A,B,C_{A \times B}R) = (A,B, \bar R) \iff a \ \bar \rho \ b \iff$ a & b nu se afla in relatie
- **Reunirea**: $\rho_1 \cup \rho_2 = (A,B,R_1 \cup R_2) \iff a \ \rho_1 \cup \rho_2 \ b \iff a \ \rho_1 \ b$ sau $a \ \rho_2 \ b$
- **Intersectia**: $\rho_1 \cap \rho_2 = (A,B,R_1 \cap R_2)$
- **Compunerea**: $(A,B,R)$ si $(B,C,G)$
  $(A,C,G \circ R)$ unde $G \circ R = \{(a,c) \in A \times C \ | \ \exists b \in B \text{ a.i. } (a,b) \in R \text{ si } (b,c) \in G\}$
	- Compunerea este [[0010 - Asociativitate, Distributivitate, Comutativitate|asociativa]]: $H \circ (G \circ R) = (H \circ G) \circ R$
