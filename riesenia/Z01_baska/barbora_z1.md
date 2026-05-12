## Maturitné zadanie 01

**1. Definujte kvadratickú funkciu. Popíšte, na akej množine môže byť definovaná a ktoré z nasledujúcich vlastností môže kvadratická funkcia spĺňať: je prostá, monotónna, má maximum, alebo minimum, je ohraničená, párna alebo nepárna?**
- kvadratická funkcia je každá funkcia s predpisom $$f: y = ax^2 + bx + c$$kde $$a, b, x \in R , a \neq 0$$
- D(f) = R   (množina reálnych čísel)
- vlastnosti:
	- prostosť - nie je prostá
	- monotónnosť - nie je monotónna
		- pre a > 0 = konvexná:
			- klesá $$x \in (-\infty : \frac{-b}{2a}>$$
			- rastie $$x \in <\frac{-b}{2a}: \infty)$$
		- pre a < 0 = konkávna:
			- intervaly sú naopak
	- extrémy: nadobúda 1 extrém (vrchol)
		- $$ [\frac{-b}{2a} : \frac {-b^2 + 4ac}{4a}]$$
		- a > 0 - minimum, a < 0 - maximum
	- ohraničenosť:
		- a > 0 - je ohraničená zdola, nie je ohraničená zhora => nie je ohraničená
		- a < 0 - je ohraničená zhora, nie je ohraničená zdola => nie je ohraničená
	- parita: párna (symetrická podľa osi y) ak b = 0

**2. Dokážte, že spojnice bodov, ktoré vyznačujú na ciferníku hodiniek čísla 11,3 a 2,6 sú na seba kolmé.**
![[1_dokaz.jpg]]
- využijeme vlastnosť: stredový uhol je dvojnásobkom obvodového
	- uhol medzi dvoma číslami ciferníka: $$\frac {360°}{12} = 30°$$
	- uhol $\alpha$:
		- $2\alpha$ - stredový uhol $\Delta$ 6,S,2
			- $2\alpha = 30°*4 = 120°$
		- $\alpha$ - obvodový uhol $\Delta$ 6,11,2
			- $\alpha = \frac {120°}{2} = 60°$ 
	- uhol $\beta$:
		- 2$\beta$ - stredový uhol $\Delta$ 6,S,3
			- $2\beta = 30°*3 = 90°$ 
		- $\beta$ - obvodový uhol $\Delta$ 6,11,3
			- $\beta = \frac {90°}{2} = 45°$ 
	- uhol $\gamma$:
		- $\alpha = \beta + \gamma => \gamma = \alpha - \beta$
		- $\gamma = 60° - 45° = 15°$
	- uhol $\phi / φ$:
		- $\Delta$ 6,S,2 - rovnoramenný trojuholník (ramená = polomer ciferníka)
		- $\phi = \frac {180° - 2\alpha}{2} = \frac {180° - 120°}{2} = \frac {60°}{2}$
		- $\phi = 30°$
	- rovnoramenný trojuholník $\Delta$ 11,S,2 = uhly $\omega$ a $\rho$:
		- $\omega$ - stredový uhol, $\omega = 30°*3 = 90°$
		- $\rho = \frac {180°-\omega}{2} = \frac{180°-90°}{2} = \frac{90°}{2} = 45°$
	- trojuholník $\Delta$ 3,2,11
		- $180° = \gamma + (\rho + \phi) + \delta$
		- $\delta = 180° - (\gamma+\rho+\phi)$
		- $\delta = 180° - (15°+30°+45°)$
		- $\delta = 180° - 90°$
		- ***$\delta = 90°$ = koniec dôkazu***


**3. Je daná postupnosť** $\Delta$
**$$\left\{ \frac{n}{n+3} \right\}_{n=1}^\infty$$**
* **zistite či je daná postupnosť ohraničená**
* **vyjadrite túto postupnosť rekurentne. Existuje aj iné rekurentné určenie danej postupnosti?**

- prvých 5 členov:
	- $$ a_1 = \frac {1}{4}$$
	- $$ a_2 = \frac {2}{5}$$
	- $$ a_3 = \frac {3}{7}$$
	- $$ a_4 = \frac {4}{8} = \frac {1}{2}$$
	- $$ a_5 = \frac {5}{9}$$
- ohraničenosť - postupnosť je ohraničená:
	- d = 0
		- v predpise (vzorci pre n-tý člen) sa nenachádza mínus - všetky členy postupnosti sú kladné
	- h = 1
		- aby bol člen väčší ako 1, čitateľ by musel byť väčší ako menovateľ
		- n > n+3 nikdy nenastane

- rekurentné určenie - 2 spôsoby:
	- $$ a_n = \frac{n}{n+3}$$
	- $$ a_{n+1} = \frac{n+1}{n+4}$$
	- rozdielom
		- $$ a_{n+1} - a_n = \frac{n+1}{n+4} - \frac{n}{n+3} = \frac{(n+1)(n+3) - n(n+4)}{(n+4)(n+3)} = \frac {n^2+4n+3 - n^2 -4n}{n^2+7n+12} = \frac{3}{n^2+7n+12}$$
		- $$ a_{n+1} = \frac{3}{n^2+7n+12} + a_n$$
	- podielom
		- $$ \frac {a_{n+1}}{a_n} = \frac {\frac{n+1}{n+4}}{\frac{n}{n+3}} = \frac{n+1}{n+4} * \frac {n+3}{n} = \frac {(n+1)(n+3)}{(n+4)n} = \frac {n^2+4n+3}{n^2+4n}$$
		- $$ a_{n+1} = \frac {n^2+4n+3}{n^2+4n} * a_n$$
