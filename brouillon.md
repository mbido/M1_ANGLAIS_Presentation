## Intro
*Damien*
## Body
### 1 - RSA
*Théo*
### 2 - Quantique
*Matthieu*
#### Intro Quantique
##### Qubits
- Classical bit -> 0 or 1
- Qubit -> vector $\in \mathbb{C}^2$ 
-  $\bra0 = \begin{bsmallmatrix} 1 & 0\end{bsmallmatrix}$
-  $\bra1 = \begin{bsmallmatrix} 0 & 1\end{bsmallmatrix}$
-  $\bra+ = \frac{1}{\sqrt{2}}\begin{bsmallmatrix} 1 & 1\end{bsmallmatrix}$
-  $\bra- = \frac{1}{\sqrt{2}}\begin{bsmallmatrix} 1 & -1\end{bsmallmatrix}$
##### Mesures
- $\bra0$ => 0 (100%)
- $\bra1$ => 1 (100%)
- $\bra+$ => 0 (50%), 1 (50%)
- $\bra-$ => 0 (50%), 1 (50%)
##### Gates
**Slide 1**
- Gate $X$
	- $X\ket0$ -> $\ket1$
	- $X\ket1$ -> $\ket0$
- Circuit
---
**Slide 2**
- Gate $H$
	- $H\ket0$ -> $\ket+$
	- $H\ket1$ -> $\ket-$
- Circuit
#### Bernstein-Vazirani
##### Problème B.V
Given the oracle of a function $f$ : 

$f : \{0, 1\}^n \rightarrow \{0, 1\}$ 
$f(x) = x\cdot s$

Find $s$ in the few request possible.

##### Algo classique
**Slide 1**
with $n=2$
try : 
- $f(10) = s_0$
- $f(01) = s_1$

2 requests.

--- 
**Slide 2**
in general : 
$\mathcal{O}(n)$ -> Try every $x$ that contains one bit to 1. At each query, we get the value of that bit in s

##### Algo Quantique
**Slide 1**
$\mathcal{O}(1)$ -> Just try every $x$ at the same time.

Not only the $x$ with only one bit at one but every possible $x$.

--- 
**Slide 2**
Circuit.

##### Shor
- Gain de complexité : 
	$\mathcal O(e^b)$ -> $\mathcal O(b³)$
- combien de qubit il faut
- combien de cubit on as

### 3 - Post-quantique
*Damien*
## Conclusion