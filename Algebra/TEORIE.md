### Multimi
$(A \cup B) \cap C = (A \cap B) \cup (A \cap C) \hspace{1cm} \text{Complementara lui X fata de E: } E \ \backslash \ X = C_E (X) = \overline X$
$\text{Legile lui de Morgan: } \overline{X \cup Y} = \overline X \cap \overline Y, \hspace{5mm} \overline{X \cap Y} = \overline X \cup \overline Y \hspace{1cm} \text{Multimea suport: } E$

### Relatii Binare
$\text{Relatie binara: un sis. ordonat } \rho = (A, B, R) \hspace{1cm} A: \text{domeniu}, B: \text{codomeniu}, R: \text{grafic}$
$\text{Relatie omogena: } A = B \hspace{5.1cm} \text{Relatie totala: } R = A \times A, \ \ A \ne \emptyset$
$\text{Relatie de egalitate/diagonala: } R = \Delta_A = \{(a,a) \ | \ a \in A\}, \ \ a \Delta_A b \iff a = b$
$R \circ \Delta_A = \Delta_B \circ R = R$
$\text{Inversa relatiei: } (B,A,R^{-1}), \text{unde } R^{-1}=\{(b,a) \in B \times A \ | \ (a,b) \in R\}$
$(R^{-1})^{-1} = R \hspace{1cm} (G \circ R)^{-1} = R^{-1} \circ G^{-1}$
$\text{(R) Reflexivitate: } a \ \rho \ a, \ \ \forall a \in A \hspace{1cm} \text{(T) Tranzitivitate: } a \ \rho \ b \text{ si } b \ \rho \ c \Rightarrow a \ \rho \ c$
$\text{(S) Simetrie: } a \ \rho \ b \Rightarrow b \ \rho \ a \hspace{2.3cm} \text{(A) Antisimetrie: } a \ \rho \ b \text{ si } b \ \rho \ a \Rightarrow a = b$
$\text{Sectiunea relatiei R dupa elementul x: } R<x> = \{y \in B \ | \ (x,y) \in R\}$
$\text{Sectiunea relatiei R dupa submultimea X: } R(X) = \{y \in B \ | \ \exists x \in X \text{ a.i. } (x,y) \in R\} = \bigcup\limits _{x \in X} R<x>$
$\text{Complementara: } \overline \rho = (A, B, \overline R) \hspace{2.4cm} a \ \overline \rho \ b \hspace{1.2cm} \iff  \text{a si b nu se afla in relatie}$
$\text{Reuniunea: } \rho_1 \cup \rho_2 = (A, B, R_1 \cup R_2) \hspace{1cm} a \ \rho_1 \cup \rho_2 \ b \iff a \ \rho_1 \ b \text{ sau } a \ \rho_2 \ b$
$\text{Intersectia: } \rho_1 \cap \rho_2 = (A,B,R_1 \cap R_2) \hspace{1cm} a \ \rho_1 \cap \rho_2 \ b \iff a \ \rho_1 \ b \ \ \text{ si } \ a \ \rho_2 \ b$
$\text{Compunerea: } G \circ R = \{(a,c) \in A \times C \ | \ \exists b \in B \text{ a.i. } (a,b) \in R \text{ si } (b,c) \in G\} \hspace{1cm} H \circ (G \circ R) = (H \circ G) \circ R$

### Relatii Functionale
$\text{Relatie functionala: } A \rightarrow B,\ \ \forall x \in A, \ |F<x> = 1| \hspace{1.5cm} \text{Functia identica: } 1_A:A \rightarrow A, \ \ 1_A(x)=x$
$\forall x \in A, \ \exists y \in B \text{ a.i. } (x,y) \in F, \ \ F=\{(x, f(x)) \ | \ x \in A\} \hspace{4.5cm} f \circ 1_A = 1_A \circ f = f$
$\text{Compusa a 2 rel. functionale este rel. functionala.} \hspace{1cm} (g \circ f)(x) = g(f(x)) \hspace{1cm} (h \circ g) \circ f = h \circ (g \circ f)$
$\text{Injectivitate: } f(x_1) = f(x_2) \Rightarrow x_1 = x_2 \ \ \text{ sau } \ \ x_1 \ne x_2 \Rightarrow f(x_1) \ne f(x_2)$
$\text{Surjectivitate: } Imf = B \hspace{1cm} \text{Bijectivitate: Inj + Surj} \ \ \text{ sau } \ \ \forall y \in B \ \exists ! \ x \in A \text{ a.i } y = f(x)$
$\text{Inversabila: } \exists f^{-1}:B \rightarrow A \text{ a.i. } f^{-1} \circ f = 1_A \text{ si } f \circ f^{-1} = 1_B \hspace{1cm} Bijectiva \iff Inversabila$
$\text{Imaginea inversa: } f^{-1}(y) = \{x \in A \ | \ f(x) = y\} \hspace{1cm} (f^{-1})^{-1} = f \hspace{1cm} (g \circ f)^{-1} = f^{-1} \circ g^{-1}$
$\text{Nr. functiilor } A \rightarrow B: |B|^{|A|} \hspace{1cm} \text{Nr. functiilor injective: } A ^{|A|} _{|B|}$

### Relatii de Echivalenta
$\text{Relatie de echivalenta: } (R)+(T)+(S) \hspace{1cm} \text{Multimea tuturor rel. de echiv.: } E(A)$
$\text{Clasa de echivalenta a lui a: } \rho<a> = \hat a = \overline a = \tilde{a} = \{x \in A \ | \ a \ rho \ x \} \hspace{0.5cm} \text{Reprezentant al clasei: a}$
$a \in \rho<a>, \ \forall a \in A \hspace{1cm} \bigcup\limits _{a \in A} \rho<a> = A \hspace{1cm} a,b \in A, \ \rho<a> = \rho<b> \iff a \ \rho \ b$
$a,b \in A, \ \text{ sau } \rho<a> = \rho<b> \ \text{ sau } \ \rho<a> \cap \rho<b> = \emptyset$
$\text{Multimea factor/cat: } A|\rho \hspace{1cm} \text{Proiectia/surjectia canonica: } A_{\rho}:A \rightarrow a|\rho, \ \ \ A_{\rho}(a) = \rho<a>$
$\text{Partitie: } \pi \in \mathcal{P}''(A), \ \text{ daca } B_1, B_2 \in \pi, \ \ B_1 \cap B_2 = \emptyset \Rightarrow B_1 = B_2 \ \text{ si } \ \bigcup\limits _{B \in \pi} B_i = A$
$\hspace{1.8cm} \mathcal{P}(A) = \{X \ | \ X \subseteq A\} \hspace{1cm} \mathcal{P}'' = \mathcal{P} \backslash \{\emptyset\} \hspace{1cm} a \ \rho_{\pi} \ b \iff \exists B \in \pi \text{ a.i. } a,b \in B \hspace{1cm} A|\rho_{\pi} = \pi$
$\text{Sistem de reprezentanti: familia de elemente } \{a_i \ | \ i \in I\} \subseteq A,$
$\hspace{5cm} \text{ daca } \forall i,j \in I, \ i \ne j \Rightarrow a_i \ \overline \rho \ a_j \ \text{ si } \ \forall x \in A, \ \exists i \in I \text{ a.i. } \ x \ \rho \ a$
  
<div style="page-break-after: always;"></div>

### Multimi Ordonate. Latici
$\text{Relatie de ordine: } (R) + (T) + (A) \hspace{1cm} \text{Not.: } (A, \le) \hspace{1cm} \text{Multime ordonata: } A$
$\text{Multime total ordonata / lant: } a \le b \text{ sau } b \le a , \ \ \forall a,b \in A$
$\text{Cel mai mic element: } \ \ \alpha \le x, \ \ \forall x \in A \ \ \rightarrow \ \ \text{Minorant / margine inferioara: } a \in A, \ \ a \le x, \ \ \forall x \in B$
$\hspace{8.2 cm} \rightarrow \ \ \text{Margine inferioara exacta: cel mai mare minorant}$
$\text{Cel mai mare element: } x \le \alpha, \ \ \forall x \in A \ \ \rightarrow \ \ \text{Majorant / margine superioara: } a \in A, \ \ x \le a, \ \ \forall x \in B$
$\hspace{8.3 cm} \rightarrow \ \ \text{Margine superioara exacta: cel mai mic majorant}$
$\text{Cel mai mic element: } 0 \hspace{1cm} \text{Cel mai mare element: } 1$
$inf B = a \Leftrightarrow \begin{cases} a \le x, & \forall x \in B \\ \alpha \le x, & \forall x \in B \ \Rightarrow \ \alpha \le a \end{cases} \hspace{2cm} sup B = a \Leftrightarrow \begin{cases} x \le a, & \forall x \in B \\ x \le \alpha, & \forall x \in B \ \Rightarrow \ a \le \alpha \end{cases}$
$\text{Latice: } (L, \le) \text{ daca } \forall x,y \in L, \ \ \exists \ inf\{x,y\} \text{ si } \exists \ sup\{x,y\} \hspace{1cm} \text{Latice completa: daca } \forall x \in L, \ \ \exists \ inf X \text{ si } \exists \ sup X$
$\text{Not.: } imf\{x,y\} = x \land y \ \ \ sup\{x,y\} = x \lor y$
$x \land y = a \Leftrightarrow \begin{cases} a \le x \text{ si } a \le y \\ \alpha \le x \text{ si } \alpha \le y \ \Rightarrow \ \alpha \le a \end{cases} \hspace{2.5cm} x \lor y = a \Leftrightarrow \begin{cases} x \le a \text{ si } y \le a \\ x \le \alpha \text{ si } y \le \alpha \ \Rightarrow \ a \le \alpha \end{cases}$

### Teoria Grupurilor
$\text{Operatie n-ara: } \forall f : A^n \rightarrow A \text{, unde } n \in N$
$\text{Asociativ: } (x * y) * z = x * (y * z) \hspace{1cm} \text{Comutativ: } x * y = y * x$
$\text{Element neutru: } x * e = e * x = x \hspace{1cm} \text{Element simetric: } x * x' = x' * x = e$
$\text{Grupoid: } (G, *), \ \ G \ne \emptyset \hspace{1cm} \text{Semigrup: } (S, *), \ \ S \ne \emptyset, \ \ Asociativ$
$\text{Monoid: } (M, *), \ \ M \ne \emptyset, \ \ \text{Asociativ,} \ \ \exists \text{ Element neutru}$
$\text{Morfism de monoizi: } f: M_1 \rightarrow  M_2, \ \ ( M_1, *), ( M_2, \circ), \ \ \displaystyle \begin{cases} f(x*y) = f(x) \circ f(y) && ,\forall x,y \in  M_1 \\ f(e_1) = e_2 \end{cases}$
$\text{Izomorfism de monoizi: morfism + bijectiv} \ \ \displaystyle \begin{cases} f \text{ inversabil} \\ \text{inversa este morfism de monoizi} \end{cases}$
$\text{Multimea elementelor simetrice: } U(M, *) = \{x \in M \ | \ x \text{ simetrizabil}\}$
$\text{Grup: } (G, *), \ \ G \ne \emptyset, \ \ \text{Asociativ,} \ \ \exists \text{ Element neutru,} \ \ \forall \text{ Element simetrizabil}$

### Subgrupuri
$\text{Subgrup: } (H \le G), \ \ G \text{ - grup,} \ \ H \subseteq G, \ \ H \ne \emptyset, \ \ \ \ H \text{ - parte stabila a lui G, grup}$
$\text{Criteriile subgrupului: } 1) \ H \le G \hspace{1cm} 2) \ x * y \in H, \ \forall x,y \in H \hspace{1cm} 3) \ x * y^{-1} \in H, \ \forall x,y \in H$
$\hspace{4.7cm} 4) \ 1 \in H \hspace{1.2cm} 5) \ x ^{-1} \in H, \ \forall x \in H$
$G \text{ - grup}, \ \ X, Y \in G \ \Rightarrow \ X * Y = \{xy \ | \ x \in X, \ y \in Y\} \hspace{1cm} X^{-1} = \{x^{-1} \ | \ x * x^{-1} = x^{-1} * x, \ \forall x \in X\}$
$\text{Altfel: } \ \  1) \ H \le G \hspace{1cm} 2) \ H * H = H \hspace{1cm} 3) \ H * H^{-1} = H$
$\text{Intersectia unei familii de subgrupuri este subgrup. } \Leftrightarrow \  H_i \le G, \ \forall i \in I \ \Rightarrow \ \displaystyle \bigcap \limits _{i \in I} H_i \le G$
$\text{Daca }H_1, \ H_2 \le G \ \Rightarrow H_1 \cap H_2 \le G \text{ dar } H_1 \cup H_2 \nleq G$
$\text{Daca } H_1, \ H_2 \le G \ \ \text{ si } H_1 \cup H_2 \le G \ \Leftrightarrow \ H_1 \subseteq H_2 \text{ sau } H_2 \subseteq H_1$
$\text{Mult. tuturor subgrupurilor lui G: } \mathcal S(G) \hspace{1cm} \text{Subgrupuri improprii: } \{1\}, G \le G$

### Subgrup Generat de X
$<X> = \bigcap \ \{H \ | \ H \le G, \ X \subseteq H\} \hspace{1cm} <X> \le G \hspace{1cm} X \subseteq <X> \hspace{1cm} X \subseteq H \le G \Rightarrow <X> \subseteq H$
$<X> = \text{ cel mai mic subgrup al lui G, care il contine pe X} \hspace{1cm} \text{Element neutru: } <X> = \{1\}$
$<X> = \text{subgrupul generat de x (croset)} = \{x_1,x_2,...,x_n \ | \ n \in \mathbb{N}^*, \ x_1,x_2,...,x_n \in X \cup X^{-1}\}$
$<X> \text{ coincide cu mult. tuturor produselor (finite) de elemente din } X \text{ sau } X^{-1} \hspace{1cm} X^{-1} = \{x^{-1} \ | \ x \in X\}$
$<X> = \{X ^k \ | \ k \in \mathbb{Z}\} = \{...,x^{-2}, x^{-1}, 0, x, x^2, ...\}$

<div style="page-break-after: always;"></div>

### Subgrup Ciclic Generat de x
$<x> = \text{ grupul ciclic generat de x: } \exists x \in G \text{ a.i. } G = <x>$
$x \in G \text{ este de ordin finit / periodic daca } \exists m \in \mathbb{N}^* \text{ a.i. } x^m = 1 \text{ (element neutru)}$
$\text{Ordinul elementului x: } ord \ x = \text{ cel mai mic m cu proprietatea anterioara}$
$ord \ x = n \Leftrightarrow x^n=1 \text{ si } x^1, x^2, ..., x^{n-1} \ne 1 \hspace{1cm} ord \ x = n \Rightarrow x^{-1} = x^{n-1}$
$\exists \text{un singur element de ordin 1, elementul neutru}$
