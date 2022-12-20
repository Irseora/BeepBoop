- Multimea vida: $\emptyset = \{x \ | \ x \ne x\}$
- **Univers**, multimea tuturor multimilor: $\mathcal{U} = \{x \ | \ x = x\}$
- $\mathbb{2} = \{0, 1\}$
	- $\mathbb{2}^A = \{f:A \rightarrow \mathbb{2}^A\}$
	- $A \subset \mathcal{U}$
- **Clasa tuturor multimilor**: $|Set|$ sau $|Ens|$

- $\mathbb{O}:A \rightarrow \mathbb{2}, \ \ \mathbb{0}(x) = 0$
- $\mathbb{1}:A \rightarrow \mathbb{2}, \ \ \mathbb{1}(x) = 1$

 - **Functia caracteristica** a multimii A: $\varphi_A:X \rightarrow \mathbb{2}, \hspace{3mm} \varphi_A(x) = \begin{cases} 1, \text{ daca } x \in A \\ 0, \text{ daca } x \notin A \end{cases}$
  $X \subset \mathcal{U}, \ A \subset X$
	  1. $\varphi_{A \cap B} = \varphi_A + \varphi_B$
	  2. $\varphi_{A \cup B} = \varphi_A + \varphi_B - \varphi_A \times \varphi_B$
	  3. $\varphi_{A / B} = \varphi_A - \varphi_A \times \varphi_B$
	  4. $\varphi_{\bar A} = \mathbb{1} - \varphi_A$
	  5. $\varphi_n = \mathbb{1}$
	  6. $\varphi_{\emptyset} = \mathbb{0}$
	  7. $\varphi_A ^2 = \varphi_A$

- $A \subset B \iff [\varphi_A(x) = 1 \Rightarrow \varphi_B(x) = 1]$
- $A = B \iff \varphi_A = \varphi_B$

- **[[004 - Implicatie|Implicatia]] lui A relativ la B**: $(A,B) \rightarrow A \rightarrow B = \bar A \cup B$
	1. $A \rightarrow (B \rightarrow A) = \mathcal{U}$
	2. $A \rightarrow (B \rightarrow C) = (A \rightarrow B) \rightarrow (A \rightarrow C) = \mathcal{U}$
	3. $A \cap B \rightarrow A = \mathcal{U}$
	4. $A \cap B \rightarrow B = \mathcal{U}$
	5. $(C \rightarrow A) \rightarrow ((C \rightarrow B) \rightarrow (C \rightarrow A \cap B)) = \mathcal{U}$
	6. $A \rightarrow A \cup B = \mathcal{U}$
	7. $B \rightarrow A \cup B = \mathcal{U}$
	8. $(A \rightarrow B) \rightarrow (\bar B \rightarrow \bar A) = \mathcal{U}$
	9. $A \rightarrow \bar A = \mathcal{U}$
	10. $\bar A \rightarrow A = \mathcal{U}$

- $A \ \Delta \ B = (A \ \backslash \ B) \cup (B \ \backslash \ A)$
	- $\varphi _{A \ \Delta \ B} = \varphi_A + \varphi_B - 2 \times \varphi_A \varphi_B$
