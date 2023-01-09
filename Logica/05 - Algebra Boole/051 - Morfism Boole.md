- **Morfism boolean**: $f:B \rightarrow B'$ unde au loc: $\hspace{1cm} \forall x,y \in B$
	1. $f(x \land y) = f(x) \land f(y)$
	2. $f(x \land y) = f(x) \land f(y)$
	3. $\overline{f(x)} = f(\bar x)$
	4. $f(0) = 0, \ \ f(1) = 1$
	
	- **Endomorfism boolean**: morfism boolean $f: B \rightarrow B$
	- **Izomorfism boolean**: morfism boolean + bijectiv $\hspace{1cm}$ Not.: $B \simeq B'$
	- **Automorfism boolean**: izomorfism boolean $f : B \rightarrow B$

- *Observatii*:
	- $f: B \rightarrow B'$ morf. boolean verifica:
		- $f(x \rightarrow y) = f(x) \rightarrow f(y)$
		- $f(x \leftrightarrow y) = f(x) \leftrightarrow f(y)$
	- $f : B \rightarrow B'$ morf. boolean $\hspace{0.3cm} \Rightarrow \hspace{0.3cm} f(B)$ subalgebra Boole a lui $B'$
	- $f : B \rightarrow B'$ morf. boolean $\hspace{.3cm} \Rightarrow \hspace{.3cm}$ U.A.S.E.:
		- $f$ injectiv
		- $x \le y \ \Leftrightarrow \ f(x) \le f(y), \hspace{1cm} \forall x,y \in B$
	- $f : B \rightarrow B'$ morf. boolean $\hspace{.3cm} \Rightarrow \hspace{.3cm}$ U.A.S.E.:
		- $f$ injectiv
		- $f^{-1}(1) = {1}$
		- $f^{-1}(0) = {0}$
