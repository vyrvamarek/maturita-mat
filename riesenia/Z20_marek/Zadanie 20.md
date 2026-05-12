## Maturitné zadanie 20

**1.** Definujte kruh a kružnicu. Pomenujte a nakreslite vzájomné polohy:

* priamky a kružnice
* dvoch kružníc

a vysvetlite všetky pojmy súvisiace s týmito polohami. <br>
Definujte kruhový výsek a odsek.

**2.** Rozhodnite o parite funkcií:
$$f:y=\frac{4x}{x^2-4}$$
$$g:y=(\cos x)-1$$
Svoje tvrdenia odôvodnite.

**3.** Daná je kocka $ABCDEFGH$ s telesovou uhlopriečkou dĺžky $2\sqrt{3}$<br>Bod $X$ je stredom hrany $EF$, bod $Y$ je stredom hrany $GH$.

1. Aký je objem telesa $XYGFC$?
2. Aký je objem telesa $XYGFA$?
3. Aký je objem telesa $XYGFBC$?

---

1. Definície
	1. Kruh
		
		![[riesenia/svg/U20kruh.svg|250]]
		
		$K(S,r)=\{ X\in \rho ;\:|SX|\le r\}$
		$r\in R,r>0$
		
		Nech je daný bod $S$ v rovine ρ a kladné reálne číslo $r$. Kruh $K$ so stredom $S$ a polomerom $r$ je množina všetkých bodov $X$ roviny $\rho$, ktorých vzdialenosť od bodu $S$ je menšia alebo rovná polomeru $r$.
		
		*Uzavretý kruh $(...≤r)$: Obsahuje aj hraničnú kružnicu (vypísaná definícia)
		Otvorený kruh $(...<r)$: Neobsahuje hraničnú kružnicu.*		
		<br>
		
	2. Kružnica
		
		![[U20kruznica.svg|250]]
		
		$k(S,r)=\{ X\in \rho ;\;|SX|=r \}$
		$r\in R,r>0$
		
		Nech je daný bod $S$ v rovine ρ a kladné reálne číslo $r$. Kružnica $k$ so stredom $S$ a polomerom $r$ je množina všetkých bodov $X$ roviny $\rho$, ktorých vzdialenosť od bodu $S$ je rovná polomeru $r$.
		
		*Stredová rovnica kruhu: $(x-m)^2+(y-n)^2=r^2$
		$S[m,n]$ ; $X[x,y]$
		<br>
		
	3. Vzájomná poloha priamky a kružnice
		
		![[U20priamkakruznica.svg|600]]
		
		Analyticky riešime vzájomnú polohu priamky a kružnice sústavou rovníc
		
		Buď ak je priamka daná parametricky: <br>
		* I. $(x-m)^2+(y-n)^2=r2$
		* II. 
			* $x=a_1+tu_1$
			* $y=a_2+tu_2$, $t\in R$
		
		Alebo ak je priamka daná všeobecnou rovnicou:
		* I. $(x-m)^2+(y-n)^2=r2$
		* II. $ax+by+c=0$
		  
		Na základe počtu riešení určujeme vzájomnú polohu, 0 - nesečnica, 1 - dotyčnica a 2 sečnica.
		
		Taktiež si môžeme vzájomné polohy zadefinovať podľa pomeru priamky k polomeru:
		
		![[U20priamkakruznica2.svg|600]]
		
		Následne to vieme použiť aj v analytike. Použijeme **vzorec na výpočet vzdialenosti bodu od priamky v rovine**
		$$|Mp|=\frac{|am_1+bm_2+c|}{\sqrt{a^2+b^2}}$$
		
		Výslednú vzidialenosť porovnáme s polomerom $r$ kružnice a určíme vzájomnú polohu priamky a kružnice.
		
		*Dôležitá poznámka: Dotyčnica je **vždy** kolmá na polomer, ktorý obsahuje bod dotyku*
		
		https://www.galeje.sk/web_object/9521.pdf
		<br>
	4. Vzájomná poloha dvoch kružníc (už nevládzem)
		
		![[/riesenia/svg/U20kruhakruh.gif]]
		
		![[U20kuzkytotozne.svg]]
		* kružnice sú totožné
		* sú sústredné a majú rovnaký polomer
		* majú nekonečno veľa spoločných bodov:
			* $k_1\cap k_2=k_1$
			* $k_1\equiv k_2$<br>
	1. Kruhový výsek
	   
	   * Časť kruhu ohraničená 2 polomermi a príslušným oblúkom
	   * Definícia cez množiny bodov:
	   $$K=\{ X\in R^2;\;|SX|\le r \}$$
	   $$Výsek=K(S,r)\cap\angle{ASB}$$
	6. Kruhový odsek
	   
	   *  Časť kruhu ohraničená tetivou a príslušným oblúkom
	   * Vznikne ako prienik kruhu a polroviny
	    $$Odsek=K(S,r)\cap polrovina(A,B)$$

2. Parita funkcií
	* O parite funkcie môžeme hovoriť iba ak spĺňa 2 podmienky:
		1. Súmernosť definičného oboru
		2. $f(-x)=f(x)$ - funkcia je párna
			$f(-x)=-f(x)$ - funkcia je nepárna
	
	* $$f:y=\frac{4x}{x^2-4}$$
		1. $D(f)=R-\{ \pm 2\}$ - súmerný okolo osi $y$
		2. Porovnanie funkčných hodnôt
		   $$f(-x)\:=\:\frac{4\cdot (-x)}{(-x)^2-4}\:=\:\frac{-4x}{x^2-4}\:=\:-\frac{4x}{x^2-4}$$
			$$-\frac{4x}{x^2-4}\: =\: f(-x)\:=\:-f(x)\;\Rightarrow funkcia\; je\; nepárna$$
			
			![[U20f.svg|250]]<br><br>
	* $$g:y=(\cos x)-1$$
		1. $D(g)=R$ - súmerný
		2. Porovnanie funkčných hodnôt
			$$g(-x)\:=\:(cos(-x))-1$$
			$$DEF: cos(-x)=cos(x)$$
			$$g(-x)\:=\:cos((-x))-1\:=\:cos(x)-1$$
			$$cos(x)-1\:=\:g(-x)\:=\:g(x)\Rightarrow\;Funkcia\;je\;párna$$
	
		![[U20g.svg|250]]<br><br>
	
3. Kocka ABCDEFGH
	* telesová uhlopriečka $2\sqrt{3}$
		* vzorec na výpočet telesovej uhlopriečky = $a\sqrt{3}$
		* $2\sqrt{3}$ = $a\sqrt{3}$
		* $a=2$
	* $X; X\in |EF|$, $|EX|=|XF|$
	*  $Y; Y\in |HG|$, $|GY|=|YH|$
	
	![[U20kocka.png|350]]
	<br>
	1. Objem telesa XYGFC
	   * Štvorboký ihlan, s podstavou $XYGF$ a vrcholom $C$
	   * $v$ = a = 2
	   * $S_p=2$
	     
	   * $V=\frac{1}{3}\cdot S_p\cdot v$
	   * $V=\frac{1}{3}\cdot 2\cdot 2$
	   * $V=\frac{4}{3}$<br>
	![[U20XYGFC.png|350]]
	<br>
	2. Objem telesa XYGFA
	   * Štvorboký ihlan, s rovnakou podstavou $XYGF$ a vrcholom $A$
	   * Rovnaký objem ako teleso XYGFC, $S_p$ a $v$ ostali rovnaké <br>
	![[XYGFA.png|350]]
	<br>
	3. Objem telesa XYGFBC
	   * Trojboký kolmý hranol, s podstavou $XFB$, jeho výška bude teda $BC$ resp. $FG$
	   * Jeho podstavu vypočítame ako trojuholník so stranou $|XF|=1$ a výškou $v=2$
	   * $S_t=1$
	   * $v=2$
	   * 
	   * $V=S_t\cdot v$
	   * $V=1\cdot 2$
	   * $V=2$<br>
	![[XYGFBC.png|350]]

