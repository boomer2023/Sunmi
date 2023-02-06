# Probabilités

## Exercice 1 

On note $D$ l'événement "j'ai un dé pipé" et $S$ l'événement "j'obtiens un 6"


$P(D|S) = \frac{P(D \cap S)}{P(S)} =  \frac{P(D)P(S|D)}{P(S)} = \frac{P(D)P(S|D)}{P(S|D)P(D) + P(S|D^c)P(D^c)}$

On a : 

$P(D) = p$

$P(D^c) = 1-p$

$P(S|D) = 1/2$

$P(S|D^c) = 1/6$

D'où la probabilité recherchée : $\frac{p/2}{p/2 + (1-p)/6} = \frac{3p}{2p+1}$  


## Exercice 2


1) Dans $\Omega$ il y a $n/d$ multiples de $d$ qui sont $d,2d,...(n/d)d$ donc $P(A_d) = (n/d)/n = 1/d$
2) On prend $A_{p_1},...A_{p_m}$ avec les $p_i$ tous distincts
$k$ est divisible par $p_1$, ... $p_m$ si et seulement si $k$ est divisible par $p_1p_2...p_m$ car les $p_i$ sont premiers entre eux.
Ainsi $$P(A_{p_1} \cap ... A_{p_m}) = P(A_{p_1...p_m}) = 1/(p_1...p_m) = P(A_{p_1})...P(A_{p_m})$$

Les événements $A_{p_i}$ sont mutuellement indépendants entre eux.

3) 
$P(\text{k est premier avec n})$


## Exercice 3


On s'intéresse qu'à $k \in [[1,n]]$
Il faut avoir tiré $k-1$ fois une boule noire puis la boule rouge.
La proba est donnée par : 
$$\frac{n-1}{n}\frac{n-2}{n-1}...\frac{n-k+1}{n-k+2}\frac{1}{n-k+1} = \frac{1}{n}$$
