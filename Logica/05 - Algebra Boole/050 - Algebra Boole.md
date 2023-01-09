- **Algebra Boole**: $(B, \lor, \land, \bar{ }, 0, 1)$ = latice distr., cu 0 si 1, in care $\forall$ el. este complementat
	$\begin{cases} x \land \bar x = 0 \\ x \land \bar x = 1 \end{cases} \hspace{1cm} \forall x \in B$
	- $C_L =$ mult. el. complementate, este o algebra Boole

- Intr-o algebra Boole definim urmatoarele operatii:
	- **Implicatie booleana**: $\rightarrow: \hspace{1cm} x \rightarrow y = \bar x \lor y$
	- **Echivalenta booleana**: $\leftrightarrow: \hspace{1cm} x \leftrightarrow y = (x \rightarrow y) \land (y \rightarrow x)$

- **Proprietati**:
	1. $\bar{\bar{x}} = x$
	2. [[001 - Legile de Morgan|Legile de Morgan]]: $\ \ \overline{x \lor y} = \bar x \land \bar y \hspace{1cm} \overline{x \land y} = \bar x \lor \bar y$
	3. $x \le y \ \Leftrightarrow \ \bar y \le \bar x$
	4. $x \le y \ \Leftrightarrow \ x \land \bar y  = 1 \ \Leftrightarrow \ \bar x \lor y = 1$
	
	1. $x \rightarrow (y \rightarrow x) = 1$
	2. $(x \rightarrow (x \rightarrow y)) \rightarrow (x \rightarrow y) = 1$
	3. $(x \rightarrow y) \rightarrow ((y \rightarrow z) \rightarrow (x \rightarrow z)) = 1$
	4. $(x \leftrightarrow y) \rightarrow (x \rightarrow y) = 1$
	5. $(x \rightarrow y) \rightarrow ((y \rightarrow x) \rightarrow (x \leftrightarrow y)) = 1$
	6. $\bar x \leftrightarrow \bar y = x \rightarrow y$
	
	1. $x \rightarrow (y \rightarrow x) = 1$
	2. $x \rightarrow (x \rightarrow y) \rightarrow (y \rightarrow x) = 1$
	3. $((x \rightarrow y) \rightarrow y) \rightarrow y = x \rightarrow y$
	4. $(x \rightarrow y) \land y = y$
	5. $x \land (x \rightarrow y) = x \land y$
	6. $(x \rightarrow y) \rightarrow y = (y \rightarrow x) \rightarrow x = x \lor y$
	7. $x \rightarrow (y \land z) = (x \rightarrow y) \land (x \rightarrow z)$
	8. $(x \lor y) \rightarrow z = (x \rightarrow z) \land (y \rightarrow z)$
	9. $x \leftrightarrow y = 1 \ \Leftrightarrow \ x = y$

- **Subalgebra Boole**: O submult. $B' \ne \emptyset$ a unei algebre Boole B daca verifica urm. axiome:
	1. $x,y \in B' \ \Rightarrow \ x \land y \in B'$
	2. $x,y \in B' \ \Rightarrow \ x \lor y \in B'$
	3. $x \in B' \ \Rightarrow \ \bar x \in B'$
	4. $0 \in B', \ \ 1 \in B'$

