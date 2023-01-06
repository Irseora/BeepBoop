## Conice
#### Conice pe ecuatia canonica (redusa)
###### Elipsa
![[elipsa.png|300]]
**Ecuatie**: $\displaystyle \frac{x^2}{a^2} + \frac{y^2}{b^2} = 1 \hspace{1cm} - dist(M,F') + dist(M,F) = 2a$
Axa mare: $AA' = 2a \hspace{1cm}$ Axa mica: $BB' = 2b \hspace{1cm}$ Focare: $FF' = 2c \hspace{1cm} a^2 - c^2 = b^2$
**Tangente**: $\displaystyle \ \frac{x_0 \ x}{a^2} + \frac{y_0 \ y}{b^2} = 1 \hspace{.5cm} \text{sau} \hspace{.5cm} y = m \ x \pm \sqrt{a^2 \ m^2 + b^2}$
**Excentricitate** = gradul de turtire a elipsei: $\displaystyle e = \frac{c}{a} = \sqrt{\frac{a^2 - b^2}{a^2}} \hspace{1cm} MF = a - e \times x$

###### Hiperbola
![[hiperbola.png|300]]
**Ecuatie**: $\displaystyle \frac{x^2}{a^2} - \frac{y^2}{b^2} = 1 \hspace{1cm} |dist(M,F) - dist(M,F')| = 2a \hspace{1cm}$
Focare: $dist(F, F') = 2c \hspace{1cm} c^2-a^2=b^2$
**Tangente**: $\displaystyle \frac{x_0 \ x}{a^2} - \frac{y_0 \ y}{b^2} = 1 \hspace{.5cm} \text{sau} \hspace{.5cm} y = m \ x \pm \sqrt{a^2 \ m^2 - b^2}$
**Excentricitate**: $\displaystyle e = \frac{c}{a} = \sqrt{\frac{a^2+b^2}{a^2}} \hspace{1cm} MF = e \times x - a$

###### Parabola
![[parabola.png|200]]
**Ecuatie**: $y^2 = 2px, \ \ \ x \ge 0 \hspace{1cm} \displaystyle dist(M,F) = dist(M,d) = \frac{|a x_0 + b y_0 + c|}{\sqrt{a^2 + b^2}}$
Focar: $\displaystyle F(\frac{p}{2}, 0)$
**Tangenta**: $y = \pm \sqrt{2px}$
**Excentricitate**: $e=1$

<div style="page-break-after: always;"></div>

#### Conice pe ecuatia generala
**Ecuatia generala**: $\Gamma: a_{11} \ x^2 + 2 \times a_{12} \ xy + a_{22} \ y^2 + 2 \times a_{13} \ x + 2 \times a_{23} \ y + a_{33} = 0$
1. Unghiul de rotatie $\Theta$:
	   $\displaystyle tg \ 2 \Theta = \frac{2 \times a_{12}}{a_{11} - 2_{22}} \hspace{.5cm} \text{sau} \hspace{.5cm} \Theta = \pi / 4$
	   $\displaystyle tg \ 2 \Theta = \frac{2 \times tg \ \Theta}{1 - tg^2 \ \Theta} = \frac{2t}{1-t^2} \hspace{1cm} tg \ \Theta = \frac{sin \ \Theta}{cos \ \Theta} = \frac{sin^2 \ \Theta}{1 - sin^2 \ \Theta} \hspace{.5cm} \Rightarrow sin \ \Theta, cos \ \Theta$
2. Ecuatiile rotatiei:
	   $\begin{cases} x = x' \ cos \ \Theta - y' \ sin \Theta \\ y = x' \ sin \ \Theta + y' \ cos \ \Theta \end{cases}$
3. Formam patrate
4. Ecuatiile translatiei:
	   $\begin{cases} x'' = x' \pm a \\ y'' = y' \pm b \end{cases}$
5. Intersectia cu reperul initial:
	   $\Gamma \cap Ox \Rightarrow y = 0 \Rightarrow M_1, M_2$
	   $\Gamma \cap Oy \Rightarrow x = 0 \Rightarrow M_3, M_4$

#### Clasificarea conicelor
**Invariantii**: $I = a_{11} + a_{22} \hspace{1cm} \delta = \begin{vmatrix} a_{11} & a_{12} \\ a_{12} & a_{22} \end{vmatrix} \hspace{1cm} \Delta = \begin{vmatrix} a_{11} & a_{12} & a_{13} \\ a_{12} & a_{22} & a_{23} \\ a_{13} & a_{23} & a_{33} \end{vmatrix}$

| **$\Delta$**                                         | **$\delta$**     | **$I$**                   | **Conica**                                    |
| ------------------------------------------------ | ------------ | --------------------- | ----------------------------------------- |
| $\Delta \ne 0$ <br /> conica <br /> nedegenerata | $\delta > 0$ | $I \times \Delta < 0$ | $\mathcal{E}$                             |
|                                                  |              | $I \times \Delta > 0$ | $\emptyset$ <br /> $(\mathcal{E} \ imaginara)$ |
|                                                  | $\delta < 0$ |                       | $\mathcal{H}$                             |
|                                                  | $\delta = 0$ |                       | $\mathcal{P}$                             |
| $\Delta = 0$ <br /> conica <br /> degenerata     | $\delta > 0$ |                       | punct                                   |
|                                                  | $\delta < 0$ |                       | drepte concurente                         |
|                                                  | $\delta = 0$ |                       | drepte paralele / <br /> confundate / $\emptyset$                                          |

<div style="page-break-after: always;"></div>

## Cercul
![[cerc 1.png|150]]
$C_0(-a, -b) \hspace{1cm} R = \sqrt{a^2 + b^2 -c}$
Ecuatia carteziana sub forma de patrate: $(x-x_0)^2 + (y-y_0)^2 = R^2$
Ecuatia carteziana generala: $x^2 + y^2 + 2ax + 2by + c = 0 \hspace{1cm} a^2 + b^2 > c$
Ecuatia prin 3 puncte necoliniare: $\displaystyle \begin{vmatrix} x^2+y^2 & x & y & 1 \\ x_1^2 + y_1^2 & x_1 & y_1 & 1 \\ x_2^2 + y_2^2 & x_2 & y_2 & 1 \\ x_3^2 + y_3^2 & x_3 & y_3 & 1 \end{vmatrix}$

#### Puterea punctului fata de cerc
![[cerc_puterea_punctului.png|200]]
$\mathcal{S}(P, \mathcal{C}(C_0, R)) = dist(C_0, P)^2 - R^2 = t_M^2$

#### Axa radicala a doua cercuri
![[axa_radicala 1.png|400]]
Locul geometric al punctelor, care au puteri egale fata de 2 cercuri date 
= o dreapta $\perp$ pe dreapta centrelor cercurilor

#### Tangenta la cerc
Tangenta in punctul $M(x_M, y_M)$:
$(x-x_0)(x_M-x_0) + (y-y_0)(y_M-y_0) = R^2 \hspace{1cm} x \cdot x_M + y \cdot y_M + a(x + x_M) + b(y+y_M) + c = 0$
Tangenta cu panta data: $y = mx \pm r \ \sqrt{1 + m^2}$

<div style="page-break-after: always;"></div>

## Dreapta & planul in spatiu
$\overrightarrow{M_1M_2} = (x_2 - x_1) \vec{i} + (y_2 - y_1) \vec{j} + (z_2 - z_1) \vec{k} \hspace{1cm} dist(M_1, M_2) = ||M_1M_2|| = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2 + (z_2-z_1)^2}$
Mijlocul unui segment: $\displaystyle M_{\text{mijloc}}(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}, \frac{z_1+z_2}{2}) \hspace{1cm} \overrightarrow{OM_{\text{mijloc}}} = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB})$
Impartirea unui segment in raport $\alpha$:
$\displaystyle \frac{AM}{MB} = \alpha \ \Rightarrow \ x_M = \frac{x_1 + \alpha \ x_2}{1 + \alpha}, \ \ y_M = \frac{y_1 + \alpha \ y_2}{1 + \alpha}, \ \ z_M = \frac{z_1 + \alpha \ z_2}{1 + \alpha} \hspace{1cm} OM = \frac{OA + \alpha \ OB}{1 + \alpha}$

#### Ecuatii
- Dreapta ce trece prin $M(x_0, y_0, z_0)$ si are directia $\vec{v}= l \vec{i} + m \vec{j} + n \vec{k}$
	  $\displaystyle \begin{cases} x = x_0 + l \cdot t \\ y = y_0 + m \cdot t \\ z = z_0 + n \cdot t \end{cases} \hspace{1.5cm} \frac{x-x_0}{l}=\frac{y-y_0}{m}=\frac{z-z_0}{n} \ (= t)$
- Dreapta determinata de 2 puncte $M1(x_1, y_1, z_1)$, $M2(x_2, y_2, z_2)$
	  $\displaystyle \begin{cases} x = (1-t)x_1 + t x_2 \\ y =(1-t)y_1 + ty_2 \\ z=(1-t)z_1 + tz_2 \end{cases} \hspace{1.5cm} \frac{x - x_1}{x_2 - x_1} = \frac{y - y_1}{y_2 - y_1} = \frac{z - z_1}{z_2 - z_1} \ (= t)$
- Planul determinat de $M_0(x_0, y_0, z_0)$ si directiile $\vec{v_1} = l_1\vec{i} + m_1\vec{j} + n_1\vec{k}$, $\ \ \vec{v_2} = l_2\vec{i} + m_2\vec{j} + n_2\vec{k}$
	  $M(x,y,z) \in \alpha \ \Rightarrow \ \overrightarrow{MM_0}, \vec{v_1}, \vec{v_2} \ \text{ coplanare } \ \Rightarrow (\overrightarrow{MM_0}, \vec{v_1}, \vec{v_2}) = 0$
	  $\overrightarrow{MM_0} = (x-x_0)\vec{i} + (y-y_0)\vec{j} + (z-z_0)\vec{k} \hspace{1.5cm} \begin{vmatrix} x-x_0 & y-y_0 & z-z_0 \\ l_1 & m_1 & n_1 \\ l_2 & m_2 & n_2 \end{vmatrix} = 0$
	  $\begin{cases} x = x_0 + l_1 t + l_2 s \\ y = y_0 + m_1 t + m_2 s \\ z = z_0 + n_1 t + n_2 s \end{cases}$
- Planul ce contine punctele $M_1(x_1, y_1, z_1)$, $\ M_2(x_2, y_2, z_2)$, $\ M_3(x_3,y_3,x_3)$ necolineare
	  $\begin{vmatrix} x & y & z & 1 \\ x_1 & y_1 & z_1 & 1 \\ x_2 & y_2 & z_2 & 1\\ x_3 & y_3 & z_3 & 1 \end{vmatrix} = 0$
- Planul determinat de o dreapta $d$ si $M_0(x_0, y_0, z_0)$
	  $\text{Se cunosc } d \text{ si } M_0 \notin d \hspace{1.5cm} \text{Luam } M_1 \in d \Rightarrow \overrightarrow{M_1M_0} = \vec{v_1}, \ \ \vec{d} = \vec{v_2}$
	  Planul va fi determinat de $M_0, \ \vec{v_1}, \ \vec{v_2}$
- Planul determinat de $d_1 \ || \ d_2$
	  $\vec{v_{d_1}} = \vec{v_{d_2}} \hspace{1cm} M_1 \in d_1, \ M_2 \in d_2 \Rightarrow \overrightarrow{M_1M_2}$
	  Planul va fi determinat de $M_1, \ \vec{v_{d_1}}, \ \overrightarrow{M_1M_2}$
- Planul ce trece prin $M_0(x_0,y_0,z_0)$ si este $\perp$ pe o directie $\vec{v} = a \vec{i} + b \vec{j} + c \vec{d}$
	  $a(x-x_0) + b(y-y_0) + c(z-z_0) = 0$
- Ecuatia generala a planului
	  $ax + by + cz + d = 0 \hspace{1cm} a^2+b^2+c^2 > 0$
	  $M_0(x_0, y_0, z_0) \in \alpha \hspace{1cm}$ **Vectorul normal** $\perp \alpha$: $\ \vec{n} = a \vec{i} + b \vec{j} + c \vec{k}$

<div style="page-break-after: always;"></div>

#### Relatii intre plane
$\alpha_1: \ a_1x + b_1y + c_1z + d_1 = 0 \hspace{1cm} \alpha_2: \ a_2x + b_2y + c_2z + d_2 = 0$
$\displaystyle \alpha_1 \ || \ \alpha_2 \ \ \Leftrightarrow \ \ \frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2} \ne \frac{d_1}{d_1}$
$\alpha_1, \ \alpha_2$ confundate $\displaystyle \ \ \Leftrightarrow \ \ \frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2} = \frac{d_1}{d_2}$
$\alpha_1 \ \cap \ \alpha_2 = d \ \ \Leftrightarrow \ \ rang \begin{pmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \end{pmatrix} = 2$

###### Fascicul de plane de axa d
![[fascicul_plane_dreapta.png|200]]
$\lambda \ (a_1x + b_1y + c_1z + d_1) + \mu \ (a_2x + b_2y + c_2z + d_2)$

###### Fascicul de plane paralele
![[fascicul_plane_paralele.png|300]]
$ax+by+cz+d+ \lambda = 0$

#### Unghiuri
- Dintre 2 drepte
	  $\displaystyle cos(d_1, d_2) = cos(\vec{v_1}, \vec{v_2}) = \frac{\vec{v_1} \cdot \vec{v_2}}{||\vec{v_1}|| \cdot ||\vec{v_2}||}$
- Dintre 2 plane
	  $\displaystyle cos(\alpha_1, \alpha_2) = cos (\vec{n_1}, \vec{n_2}) = \frac{\vec{n_1} \cdot \vec{n_2}}{||\vec{n_1}|| \cdot ||\vec{n_2}||}$
- Dintre dreapta si plan
	  $\displaystyle sin (d, \alpha) = cos (\vec{v}, \vec{n}) = \frac{\vec{v} \cdot \vec{n}}{||\vec{v}|| \cdot ||\vec{n}||}$

<div style="page-break-after: always;"></div>

#### Distante
- Dintre punct si dreapta
	  ![[dist_punct_dreapta.png|300]]
	  Fie $M_0 \in d$, $\ \ \vec{v}$ directia lui $d$
	  $A_{\text{paralelogram}} = || \vec{v} \times \overrightarrow{M_0A} || = || \vec{v} || \cdot dist (A,d)$
- Dintre punct si plan
	  ![[dist_punct_plan.png|300]]
	  $M_0(x_0,y_0,z_0) \hspace{1cm} \alpha: \ ax+by+cz+d=0 \Rightarrow \vec{n} = a \vec{i} + b\vec{j} + c\vec{k}$
	  $\displaystyle dist(M_0, d) = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2+b^2+c^2}}$

<div style="page-break-after: always;"></div>

## Produse de vectori
#### Produsul scalar
$\vec{a} \cdot \vec{b} \ = \ a_1 b_1 + a_2 b_2 + a_3 b_3 \ = \ \begin{cases} 0, & \text{daca } \vec{a} = 0 \text{ sau } \vec{b} = 0 \\ ||\vec{a}|| \cdot ||\vec{b}|| \cdot cos(\vec{a}, \vec{b}), & \text{altfel} \end{cases}$
$\displaystyle cos(\vec{a}, \vec{b}) = \frac{\vec{a} \cdot \vec{b}}{||\vec{a}|| \cdot ||\vec{b}||} \hspace{1cm} ||\vec{v}|| \ = \ \sqrt{\vec{v} \cdot \vec{v}} \ = \ \sqrt{a_1^2 + a_2^2 + a_3^2} \hspace{1cm} \vec{v}^2 = ||\vec{v}||^2$

1. Comutativ: $\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a}$
2. Distributiv: $\vec{a} \cdot (\vec{b} + \vec{c}) = \vec{a} \cdot \vec{b} + \vec{a} \cdot \vec{c}$
3. $\lambda (\vec{a} \cdot \vec{b}) = (\lambda \ \vec{a}) \cdot \vec{b} = \vec{a} \cdot (\lambda \ \vec{b})$
4. $\vec{a} \cdot \vec{a} = ||\vec{a}||^2 \ge 0 \hspace{1.5cm} \vec{a} \cdot \vec{a} = 0 \ \Leftrightarrow \ \vec{a} = 0$
5. $\vec{a} \cdot \vec{b} = 0 \ \Leftrightarrow \vec{a} \perp \vec{b} \hspace{1cm} (cos (\pi / 2) = 0)$

#### Produsul vectorial
$\vec{a} \times \vec{b} = \begin{vmatrix} \vec{i} & \vec{j} & \vec{k} \\ a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \end{vmatrix} \ = \ \begin{cases} 0, & \text{daca } \vec{a}, \vec{b} \text{ coliniari} \\ ||\vec{a}|| \cdot ||\vec{b}|| \cdot sin(\vec{a}, \vec{b}) \cdot \vec{v_0}, & \text{altfel} \end{cases}$
$||\vec{a} \times \vec{b}|| = 2 \cdot A_\Delta = A_{\text{paralelogram}} \hspace{1cm} \vec{i} \times \vec{j} = ||\vec{i}|| + ||\vec{j}|| + sin(\vec{i}, \vec{j}) = 1$

1. Anticomutativ: $\vec{a} \times \vec{b} = -\vec{b} \times \vec{a}$
2. $\vec{a} \times (\alpha \ \vec{b}) = (\alpha \ \vec{a}) \times \vec{b} = \alpha \ (\vec{a} \times \vec{b})$
3. $\vec{a} \times \vec{a} = 0$
4. Distributiv: $\vec{a} \times (\vec{b} + \vec{c}) = \vec{a} \times \vec{b} + \vec{a} \times \vec{c}$
5. $\vec{a} \times \vec{0} = \vec{0} \times \vec{a} = \vec{0}$

###### Produsul dublu vectorial
$\vec{a} \times (\vec{b} \times \vec{c}) \ = \ \begin{vmatrix} \vec{b} & \vec{c} \\ \vec{a} \cdot \vec{b} & \vec{a} \cdot \vec{c} \end{vmatrix} \ = \ (\vec{a} \cdot \vec{c}) \cdot \vec{b} - (\vec{a} \cdot \vec{b}) \cdot \vec{c}$
Permutare circulara: $\vec{a} \times (\vec{b} \times \vec{c}) + \vec{b} \times (\vec{c} \times \vec{a}) + \vec{c} \times (\vec{a} \times \vec{b}) = 0$

1. 2x Anticomutativ: $(\vec{a} \times \vec{b}) \times \vec{c} = \vec{c} \times (\vec{b} \times \vec{a})$
2. $(\vec{a} \times \vec{b}) \cdot (\vec{c} \times \vec{d}) \ = \ \begin{vmatrix} \vec{a} \cdot \vec{c} & \vec{a} \cdot \vec{d} \\ \vec{b} \cdot \vec{c} & \vec{b} \cdot \vec{d} \end{vmatrix} \ = \ (\vec{b} \cdot \vec{d}) \cdot (\vec{a} \cdot \vec{c}) - (\vec{b} \cdot \vec{c}) \cdot (\vec{a} \cdot \vec{d})$
3. $\vec{a} \times (\vec{b} \times \vec{c}) \ne (\vec{a} \times \vec{b}) \times \vec{c}$
4. $(\vec{a} \times \vec{b}) \times \vec{c} = - \vec{c} \times (\vec{a} \times \vec{b})$

#### Produsul mixt
$(\vec{a}, \vec{b}, \vec{c}) \ = \ \begin{vmatrix} a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \\ c_1 & c_2 & c_3 \end{vmatrix} \hspace{2cm}$ Permutare circulara: $(\vec{a}, \vec{b}, \vec{c}) = (\vec{b}, \vec{c}, \vec{a}) = (\vec{c}, \vec{a}, \vec{b})$
$|(\vec{a}, \vec{b}, \vec{c})| = V_{\text{paralelipiped}} = 6 \cdot V_{\text{tetraedru}} \hspace{1cm} (\vec{a}, \vec{b}, \vec{c}) = 0 \ \Leftrightarrow \ \vec{a}, \vec{b}, \vec{c} \text{ coplanari}$
$(\vec{a}, \vec{b}, \vec{c}) = -(\vec{b}, \vec{a}, \vec{c})$

