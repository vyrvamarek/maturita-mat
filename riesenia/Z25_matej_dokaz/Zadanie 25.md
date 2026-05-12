**1.** Definujte pojmy výrok, pravdivostná hodnota výroku, negácia výroku, zložený výrok, kvantifikovaný výrok. Vysvetlite pojmy: konjunkcia, disjunkcia, implikácia, ekvivalencia výrokov a uveďte príklady.

**2.** Dokážte, že ťažnica ľubovoľného trojuholníka je menšia, ako polovica jeho obvodu.

**3.** Daná je kocka ABCDEFGH tak, že $A[2; 0; 0]$, $B[2; 2; 0]$, $C[0; 2; 0]$. Určte súradnice ostatných vrcholov kocky, vypočítajte:

* vzdialenosť bodov S, D, ak S je stred úsečky AB
* vzdialenosť bodu H od telesovej uhlopriečky, ktorá ním neprechádza.

Ako sa zmenia súradnice vrcholov kocky, ak $A[0;0;0]$

_________________________________________________________________________

**TEÓRIA**
Výrok: 
- Tvrdenie v tvare oznamovacej vety, o pravdivosti ktorého má zmysel uvažovať .

Pravdivostná hodnota výroku: 
- Výrok môže byť buď pravdivý (1), alebo nepravdivý (0).

Negácia výroku: 
- Upravenie výroku tak, aby mal opačné pravdivostné hodnoty ako mal pôvodný.
- Zahrňuje všetky ostatné situácie, ktoré môžu nastať ako mal originálny.

Zložené výroky: 
- Výroky vytvorené spojením jednoduchých výrokov pomocou logických spojok.
- Druhy:
	- Konjunkcia $A \land B$
    	- Zložený výrok, ktorý vznikne spojením dvoch alebo viacerých výrokov spojkou a; i; aj; a súčasne.
    	- “Mám veľa kamarátov a dobré známky.”
    	- Negácia: Inkluzívna disjunkcia znegovaného prvého a znegovaného druhého výroku -> $A' \lor B'$
	- Disjunkcia $A \lor B$
		- Zložený výrok, ktorý vznikne spojením dvoch alebo viacerých výrokov spojkou alebo; či.
		- “Mám ceruzku alebo pero.”
		- Negácia: Konjunkcia znegovaného prvého a znegovaného druhého výroku -> $A' \land B'$
		- $\lor$ -> alebo (inkluzívna disjunkcia)
		- $\veebar$ -> buď, alebo (exkluzívna disjunkcia)
	- Implikácia $A \implies B$
		- Zložený výrok, ktorý vznikne spojením dvoch výrokov tak, že pred prvý výrok predradíme slovo “ak” a pred druhý predradíme slovo “tak” alebo nepredradíme nič.
		- “Ak prší, tak je mokro.”
		- Negácia: Konjunkcia prvého a znegovaného druhého výroku -> ($A \land B'$)
		- Obrátená implikácia: implikácia druhého a prvého výroku
		- Obmena implikácie: implikácia znegovaného druhého a znegovaného prvého výroku (rovnaká pravdivostná hodnota ako originálna implikácia)
	- Ekvivalencia $A \iff B$ - obojstranná implikácia
		- Zložený výrok, ktorý vznikne spojením dvoch výrokov tak, že za prvý výrok priradíme slovné spojenie “vtedy a len vtedy/práve vtedy” a pred druhý predradíme slovo “keď”.
		- “Jednotku z písomky dostanem práve vtedy, keď sa budem učiť.”
		- Negácia: Inkluzívna disjunkcia konjunkcie prvého a znegovaného druhého výroku a konjunkcie druhého a znegovaného prvého výroku -> ($A \land B'$) $\lor$ ($B \land A'$) | Exkluzívna disjunkcia prvého a druhého výroku -> $A \veebar B$

Kvantifikovaný výrok: 
- Vyjadrujú počet alebo rozsah objektov, pre ktoré platí určitá vlastnosť.
- Hovoria o množstve, negujeme počet.
- Obsahujú kvantifikátory: 
	- Všeobecný: ∀ (všetci, každý, ľubovoľný)
	- Existenčný: ∃ (existuje aspoň 1) | ∃! (existuje práve jeden)


**DÔKAZ**
![[Z25_dôkaz.svg]]
**PRÍKLAD**
a)
$A[2; 0; 0]$, $B[2; 2; 0]$, $C[0; 2; 0]$ -> $D[0; 0; 0]$, $E[2; 0; 2]$, $F[2; 2; 2]$, $G[0; 2; 2]$, $H[0; 0; 2]$


$S_{AB} \in AB; |AS| = |SB|$
$A[2; 0; 0]$, $B[2; 2; 0]$
$|S_{AB}D| = ?$

$S_{AB} = (\frac{2+2}{2};\frac{0+2}{2};\frac{0+0}{2})$
$S_{AB}[2;1;0]$
$D[0; 0; 0]$
$|S_{AB}D| = \sqrt{(2+0)^2+(1+0)^2+(0+0)^2}$
$|S_{AB}D| = \sqrt{5}$


c)
DF - uhlopriečka neprechádzajúca bodom H
$\vec{DF} = \vec{F} - \vec{H} = (2-0;2-0;2-0) = (2;2;2)$
$\vec{DF}:$
$x = 0+2k = 2k$
$y = 0+2k = 2k$
$z = 0+2k = 2k$       $k \in R$

určíme si bod, ktorý bude priesečníkom kolmice, ktorá prechádza cez H a uhlopriečky
$P \in \vec{DF}; P[2k; 2k; 2k]$ -> lebo je na uhlopriečke DF
$\vec{PH} = (2k-0; 2k-0, 2k-2)$
$\vec{DF} . \vec{PH} = 0$ -> aby boli kolmé, ich skalárny súčin musí byť 0
$2.(2k-0) + 2.(2k-0) + .2(2k-2) = 0$
$4k + 4k + 4k - 4 = 0 /+4$
$12k = 4 /:12$
$k = \frac{1}{3}$

dosadíme do parametrického vyjadrenia priamky
$x = 2.\frac{1}{3} = \frac{2}{3}$
$y = 2.\frac{1}{3} = \frac{2}{3}$
$z = 2.\frac{1}{3} = \frac{2}{3}$
$P[\frac{2}{3}; \frac{2}{3}; \frac{2}{3}]$

vypočítame vzdialenosť dvoch bodov
$|HP| = \sqrt{(\frac{2}{3}-0)^2 + (\frac{2}{3}-0)^2 + (\frac{2}{3}-2)^2}$
$|HP| = \frac{2\sqrt{6}}{3} \doteq 1,63$


d)
posunieme x-ové súradnice všetkých bodov o -2
$A[0; 0; 0]$, $B[0; 2; 0]$, $C[-2; 2; 0]$, $D[-2; 0; 0]$, $E[0; 0; 2]$, $F[0; 2; 2]$, $G[-2; 2; 2]$, $H[-2; 0; 2]$