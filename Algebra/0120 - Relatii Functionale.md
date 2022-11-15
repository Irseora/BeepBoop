 - **Relatie functionala / aplicatie / functie**: $\rho = (A,B,F), \hspace{5mm} A \rightarrow B, \ \forall x \in A, \ |F<x>|=1$
	 - Notat: $f(x)$
	 - $F = \{(x, f(x) \ | \ x \in A\}$
- Compusa a 2 relatii functionale este relatie functionala
- **Functia identica** pe A: $\ 1_A: A \rightarrow A$
	- Functia identica actioneaza ca element neutru: $f \circ 1_A = 1_A \circ f = f$
 
### ![[0020 - Injectivitate, Surjectivitate, Bijectivitate|]]
- **Imaginea lui X prin f**: $f:A \rightarrow B, \ X \subseteq A, \ Y \subseteq B$
  $f(X) = \{f(x) \ | \ x \in X\} = \{y \in B \ | \ \exists x \in X \text{ a.i. } y = f(x)\}$
	- Daca $X = A \Rightarrow f(A) = Im \ f$
- **Imaginea inversa / contraimaginea lui Y prin f**: $f^{-1}(Y) = \{x \in A \ | \ f(x) = Y\}$

- Functia $f:A \rightarrow B$ este **inversabila**, daca $\exists g:B \rightarrow A \text{ a.i.} \begin{cases} g \circ f = 1_A \\ f \circ g = 1_B \end{cases}$
	- g este unic determinat, notat $f^{-1}$
	- f inversabila $\iff$ f bijectiva
	- $f:A \rightarrow B \text{ inv. } \Rightarrow f^{-1}:B \rightarrow A \text{ inv. si } (f^{-1})^{-1} = f$
	- $f,g \text{ inv. } \Rightarrow g \circ f \text{ inv. si } (g \circ f)^{-1} = f^{-1} \circ g^{-1}$
