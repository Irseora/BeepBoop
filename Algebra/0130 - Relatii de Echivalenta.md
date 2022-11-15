- **Relatie de echivalenta**: [[0111 - Reflexiv, Tranzitiv, Simetric, Antisimetric|Reflexiv + Tranzitiv + Simetric]]
	- $E(A)$ = multimea relatiilor de echivalenta pe A
	- $\rho <a> = \hat{a} = \bar a = \tilde{a}$
- **Clasa de echivalenta** a lui a: $\rho <a> = \{x \in A \ | \ a \ \rho \ x\}$
	- $a \in A$ este **reprezentant** al clasei

- Fie $\rho \in E(A)$ atunci are loc:
	1. $a \in \rho<a>, \ \forall a \in A$
	2. $a,b \in A, \ \rho<a> = \rho<b> \iff a \ \rho \ b$
	3. $a,b \in A,$ sau $\rho <a> = \rho <b>$ sau $\rho <a> \cap \ \rho <b> = \emptyset$
	4. $\cup _{a \in A} \ \rho <a> = A$

- **Multimea factor / cat** a lui A in raport cu $\rho$: *$A|\rho$*
- **Proiectia / surjectia canonica**: *$A \rightarrow A|\rho$*

- **Partitia lui A**: $A \ne \emptyset$ si $\pi \in \mathcal{P}''(A)$
	1. $B_1, B_2 \in \pi, \ \ B_1 \cap B_2 = \emptyset \Rightarrow B_1 = B_2$
	2. $\cup _{B \in \pi} B_i = A$
- Observatii:
	- $\mathcal{P}(A) = \{X \ | \ X \subseteq A\}$
	- $\mathcal{P}(A)'' = \mathcal{P}(A) - \emptyset$
	- $\rho \in E(A) \Rightarrow A|\rho$ partitie lui A
	- $\pi$ partitie: $a \ \rho \ b \iff \exists b \in \pi \text{ a.i. } a,b\in B \hspace{3mm} \rho_{\pi} \in E(A) \text{ si } A|\rho_{\pi} = \pi$

- **Sistem de reprezentanti**: $\{a_i \ | \ i \in I\}$ este sistem de reprezentanti pentru $\rho$ daca
	1. $\forall i, j \in I, \ i \ne j \Rightarrow a_i \ \rho \ a_j$
	2. $\forall x \in A, \ \exists i \in I \text{ a.i. } x \ \rho \ a_i$
