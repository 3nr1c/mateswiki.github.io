---
layout: post
title:  "Corbes paramètriques a $R^n$"
author: Arnau Sistach Reinsoso
layout: math
---
# Corba paramètrica a $\Re^n$ en $[a, b]$: $\gamma(t)$
## Definició
- $a, b \in \Re: a < b$
- $$\begin{array}{rccc}
\gamma:&[a,b] &\to& \Re^n \\
& t &\mapsto& \gamma(t)
\end{array}
$$
- $\gamma \in C^1([a, b])$

## Altres Definicions

| Definició | Representació |
|---------|-------------|
| Interval del paràmetre | $[a, b]$ |
| Recorregut o trajectòria | $\gamma([a, b]) = \gamma^* =$ Im$(\gamma)$ |
| Punt inicial de la corba | $\gamma(a)$ |
| Punt final de la corba | $\gamma(b)$ |
| Corba tancada | $\gamma(a) = \gamma(b)$ |
| Corba simple | Injectiu (sense autointerseció) |

# Corba oposada o inversa: $-\gamma(t)$
## Definició
- $\gamma$ una corba paramètrica a $\Re^n$ en $[a, b]$
- $$\begin{array}{rccc}
-\gamma:&[a,b] &\to& \Re^n\\
& t &\mapsto& -\gamma(t) = \gamma(a+b-t)
\end{array}
$$

## Propietats
- $(-\gamma)^* = \gamma^*$

# Juxta posició (o suma) dues corbes $\alpha$ i $\beta$: $\alpha \vee \beta$
## Definició
- $$\begin{array}{rccc}
\alpha:&[a,b] &\to& \Re^n\\
& t &\mapsto& \alpha(t)
\end{array}
$$
- $$\begin{array}{rccc}
\beta:&[c,d] &\to& \Re^n\\
	& t &\mapsto& \beta(t)
\end{array}
$$
- $\alpha(b) = \beta(c)$
- $$\begin{array}{rcccl}
(\alpha \vee \beta):&[a,b+(d-c)] &\to& \Re^n\\
	& t &\mapsto& (\alpha \vee \beta)(t)
		&=\begin{cases}
		\alpha(t)	&\quad \text{si } t \in [a, b] \\
		\beta(t -b +c)	&\quad \text{si } t \in [c, d] \\
		\end{cases}
\end{array}
$$

# Canvi de paràmetres: $\varphi$
## Definició
- $\gamma:[a,b] \to \Re^n$ una corba paramètrica
- $\varphi:[c,d] \to [a,b]$
  - bijectiva
  - $\varphi \in C^1([c,d])$
  - $\varphi^{-1} \in C^1([a,b])$
## Propietats
- $$\forall u \in [c,d] \quad \Rightarrow
\begin{cases}
\varphi'(u) < 0\\
\text{un o l'altre, mai els dos}\\
\varphi'(u) > 0\\
\end{cases}
$$
- Canvia la velocitat

# Logitud d'una corba: $l(\gamma)$
