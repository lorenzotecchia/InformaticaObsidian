---
author: Simone Parente, Mario Penna
tags:
  - algebra/classi/teorema
---
Sia $m \in \mathbb{N} \backslash \{0\}$ e sia $a \in \mathbb{Z} \backslash \{\overline{0}\}$.
$\overline{a}$ è invertibile in $Z_m \iff MCD(a,m)[>0]=1$
#### Dimostrazione $\textcolor{red}{\implies}$
$\overline{a}$ è invertibile $\overset{def}{\iff} \exists \overline{b} \in \mathbb{Z}_m : \overline{b} \cdot \overline{a} = \overline{1} \implies \exists \overline{b} \in \mathbb{Z}_m : \overline{ab} = \overline{1}$ 
$\implies \exists b \in \mathbb{Z} : m|ab-1$
$\implies m|ab-1 \iff \exists b,h \in \mathbb{Z}:ab-1=mh \implies 1=ab-mh$
Per il [[Teorema di Bezout|teorema di Bezout]] $\implies \exists h,k \in \mathbb{Z} (ah \cdot mk = 1) \implies a,m$ sono [[Numeri coprimi|coprimi]] $\implies MCD(a,m)=1$.
#### Dimostrazione $\textcolor{red}{\impliedby}$
$MCD(a,b) = 1 \implies \exists h,k \in \mathbb{Z} (1=ha+km)$
$\implies \overline{1} = \overline{ha+km} \implies \overline{1} = \overline{h} \overline{a} + \overline{k}\overline{m}$
Dove $\overline{k} \overline{m} = 0$, di conseguenza $\overline{a}$ è invertibile, con inverso $k$.

#### Esercizio
Sia $\mathbb{Z}_6$ l'insieme delle classi di resto di $6$, cioè:
$$\mathbb{Z}_6\{\overline{1},\overline{2},\overline{3},\overline{4},\overline{5}\}$$
L'insieme degli invertibili $U(Z_6)$ è l'insieme degli elementi definiti come:
$$\exists x \in \mathbb{Z}_6:MCD(x,6)=1$$
$$MCD(0,6)=6\neq1$$
$$\textcolor{green}{MCD(1,6)=1}$$
$$MCD(2,6)=2\neq1$$
$$MCD(3,6)=3\neq1$$
$$MCD(4,6)=2\neq1$$
$$\textcolor{green}{MCD(5,6)=1}$$
Quindi l'insieme $U(\mathbb{Z}_6)=\{\overline{1},\overline{6}\}$.