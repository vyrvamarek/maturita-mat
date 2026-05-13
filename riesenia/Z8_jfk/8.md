1. Definujte lineárnu funkciu. Popíšte, na akej množine môže byť definovaná a ktoré z nasledujúcich vlastností môže lineárna funkcia spĺňať: je prostá, párna, monotónna, má maximum, alebo minimum, je ohraničená? Daná je funkcia f: y = 2x + 3; x $\in$ (-7;3>. - Určte D(f), H(f) a popíšte, ktoré z hore uvedených vlastností funkcia f spĺňa.
2. Dokážte, že trojciferné číslo „xyz", kde x, y, z sú jeho cifry, je deliteľné tromi práve vtedy, keď súčet x + y + z je deliteľný tromi. Návod : použite desiatkový rozklad čísla xyz.
3. Vypočítajte obsah trojuholníka ABC a veľkosť uhla ẞ, ak A[3,2], B[-1,1] a C[11,-6]. Ako treba zmeniť y-ovú súradnicu bodu C, aby trojuholník ABC bol pravouhlý s pravým uhlom pri vrchole B?


1.
Lineárna funkcia:
- Každá funkcia definovaná na množine reálnych čísel $\Bbb{R}$ , ktorá je daná predpisom: $f: y = ax + b; a,b \in \Bbb{R}$ 
- vlastnosti:
	- Vždy prostá, pokiaľ je smernica funkcie nenulová
	- Monotónna - ak je smernica väčšia ako 0, funkcia je rastúca, ak je menšia ako 0, funkcia je klesajúca, a ak je nulová, funkcia je konštantná
	- Párna iba ak je smernica nulová; Nepárna iba ak je $b$ nulové
	- Pokiaľ je funkcia definovaná na celom obore reálnych čísel $\Bbb{R}$ , tak nenadobúda extrémy
	- Pokiaľ je funkcia definovaná na celom obore reálnych čísel $\Bbb{R}$ , tak je ohraničená iba ak je smernica nulová


$f: y = 2x + 3; x \in (-7;3\rangle$
$D(f):$ $(-7;3\rangle$
$H(f): (-11; 9\rangle$

Vlastnosti:
- Je prostá
- Je monotónna
- Nie je párna ani nepárna
- Nadobúda maximum v bode [3; 9]
- Je ohraničená zdola, je ohraničená zhora; je ohraničená



2.
$\forall x, y, z \in \Bbb{R}; ^3/x+y+z \implies ^3/xyz$

Nech:
$(x + y + z) = 3k; k \in \Bbb{N}$ 

$xyz = x \cdot 100 + y \cdot 10 + z = 99 \cdot x + 9 \cdot y + (x + y + z) = 99 \cdot x + 9 \cdot y + 3 \cdot k = 3 \cdot (33 \cdot x + 3 \cdot y + k)$ 

$xyz = 3 \cdot (33 \cdot x + 3 \cdot y + k)$
$^3/ 3 \cdot (33 \cdot x + 3 \cdot y + k) \implies ^3/ xyz$ čbtd



3.
$\triangle$ ABC
A[3; 2]
B[-1; 1]
C[11; -6]

![[Pasted image 20260513152341.png]]

$a = \sqrt{ (-1 - 11)^2 + (1 - (-6))^2 }$
$a = \sqrt{ (-12)^2 + 7^2 }$
$a = \sqrt{ 144 + 49 }$
$a = \sqrt{ 193 }$

$b = \sqrt{ (11 - 3)^2 + ((-6) - 2)^2 }$
$b = \sqrt{ 8^2 + (-8)^2 }$
$b = \sqrt{ 64 + 64 }$
$b = \sqrt{ 2 \cdot 64 }$
$b = 8 \sqrt{ 2 }$

$c = \sqrt{ (3 - (-1))^2 + (2 - 1)^2 }$
$c = \sqrt{ 4^2 + 1^2 }$
$c = \sqrt{ 16 + 1 }$
$c = \sqrt{ 17 }$

S = ?
$\beta$ = ?

$b^2 = a^2 + c^2 - 2 a c \cos{ \beta }$ 
$\beta = \cos^{-1} {b^2 - a^2 -c^2 \over -2ac}$
$\beta = \cos^{-1} {(8 \sqrt{2} )^2 - \sqrt{193} ^2 - \sqrt{17} ^2 \over -2 \sqrt{193} \cdot \sqrt{17}}$
$\beta = \cos^{-1} {128 - 193 - 17 \over -2 \sqrt{193 \cdot 17}}$
$\beta = \cos^{-1} {83 \over 2 \sqrt{ 3281 }}$
$\beta \doteq 43,57°$

$\sin \beta = {v \over c}$
$v = \sin \beta \cdot c$
$v = \sin 43,57° \cdot \sqrt{ 17 }$
$v \doteq 2,84$ 

$S = {a \cdot v \over 2}$
$S = { \sqrt{193} \cdot 2,84 \over 2 }$
$S \doteq 19,74$

========================

$\beta = 90°$
A[3; 2]
B[-1; 1]
C[11; y]

$\vec{BA} \cdot \vec{BC}$ = 0
$(3 - (-1); 2 - 1) \cdot (11 - (-1); y - 1) = 0$
$(4; 1) \cdot (12; y-1) = 0$
$4 \cdot 12 + 1 \cdot (y-1) = 0$
$48 + y - 1 = 0$
$y = -47$

C[11; -47]