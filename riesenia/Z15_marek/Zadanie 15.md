## Maturitné zadanie 15

**1.** Definujte logaritmickú funkciu. Povedzte na akej množine je definovaná a aké hodnoty nadobúda. Popíšte graf a uveďte, ktoré z uvedených vlastností, môže logaritmická funkcia spĺňať: je prostá, monotónna, má maximum, alebo minimum, je ohraničená, párna, alebo nepárna. 

Určte inverznú funkciu k funkcii $f:y=(\frac{1}{2})^x$ a načrtnite jej graf.

**2.** Dané sú tri priamky $k$,$l$,$m$, pričom priamky $k$ a $m$ sú rovnobežné, priamka $l$ je s nimi rôznobežná. Zostrojte všetky *rovnostranné trojuholníky* $ABC$, v ktorých ťažnica $t_c$​ je časťou priamky $m$, a vrcholy $A$,$B$ ležia postupne na priamkach $k$,$l$.

**3.** Osovým rezom valca je obdĺžnik s uhlopriečkou dĺžky $20 cm$. Výška valca je *2-krát väčšia* než *priemer podstavy*. Vypočítajte objem valca v **litroch**. 

*Ako sa zmení* objem valca, ak sa daná uhlopriečka **zdvojnásobí**?

---

1. Definícia
	* $f:y=log_ax$
	  $a\in R^+-\{ 1 \}$
	  $x>0$<br>
	* je to inverzná funkcia k exponenciálnej funkcii ($f:y=a^x\rightarrow f^{-1}:x=a^y$)
		* tým že je to inverzná funkcia, má opačné obory k tým exponenciálnej funkcie
		* $D(f_e)=R\rightarrow H(f_l)=R$
		* $H(f_e)=(0;\infty)\rightarrow D(f_l)=(0;\infty)$<br>
	* graf funkcie je **logaritmická krivka** - jej poloha a tvar závisí od hodnoty $a$
		1. Ak $a>1\rightarrow$ funkcia je rastúca 
		2. Ak $1>a>0\rightarrow$ funkcia je klesajúca
		* v oboch prípadoch krivka prechádza bodom $[1;0]$
		* graf je ohraničený **osou y** $\rightarrow$ x nesmie byť nikdy záporné
	* vlastnosti funkcie
		* Je prostá
			* každej hodnote $y$ prislúcha práve jedna hodnota $x$
			* z tejto vlastnosti vyplýva existencia inverznej funkcie
		* Je monotónna
			* rastúca pre $a>1$
			* klesajúca pre $1>a>0$
		* Maximum a minimum nedosahuje
			* $H(f_l)=R$
		* Nieje ohraničená
		* Nieje párna ani nepárna
			* nespĺňa podmienku súmerného definičného oboru
	* Inverzná funkcia
		* $$f:y=(\frac{1}{2})^x\rightarrow f^{-1}:x=(\frac{1}{2})^y$$
		* $$f^{-1}:x=(\frac{1}{2})^y\rightarrow \log_\frac{1}{2}x=y$$
		* $$f^{-1}:y=\log_\frac{1}{2}x$$
		* ![[/riesenia/svg/U15f-1.png|550]]<br>
2. Konštrukčná úloha
		$$D: k,l,m; k\parallel m;k\nparallel l \land m\nparallel l$$$$Ú:\forall \; \triangle ABC;\;|AB|=|BC|=|AC|;\;t_c\in m;\;A\in k;\;B\in l$$
	* Rozbor
		* $A\in k\cap l'$
		* $B\in l\cap k'$
		* $A\in m\cap k_d(A;|AB|)$<br>	
	* Postup
		1. $k,l,m; k\parallel m;k\nparallel l \land m\nparallel l$
		2. $O_{m}\;k\rightarrow k'$
		3. $O_{m}\;l\rightarrow l'$
		4. $A, A\in k\cap l'$
		5. $B, B\in l\cap k'$
		6. $k_d(A;|AB|)$
		7. $C,C\in k_d\cap m$
		8. $\triangle ABC$<br>
	![[/riesenia/svg/U15konst.png|600]]<br>
	Táto úloha má 2 riešenia. - otázka diskusie (bavili sme sa o tom v chate)
3. Príklad
	* Rez valca = obdĺžnik $ABCD$
	* $|AC|=20cm$
	* $V_v=?$L
	* $r_{S_p}=?$
	* $r_{S_p}=\frac{x}{2}$
	* $v=?$
	* $v=2x$<br><br>![[/riesenia/svg/U15priklad.svg|400]]<br>
	* $a^2+b^2=c^2$
	* $x^2+v^2=20^2$
	* $x^2+(2x)^2=400$
	* $5x^2=400$
	* $x^2=80$
	* $x=4\sqrt{5}$<br><br>
	* $V_v=\pi r^2\cdot v$
	* $V_v=\pi (\frac{x}{2})^2\cdot 2x$
	* $V_v=\pi (\frac{4\sqrt{5}}{2})^2\cdot 2(4\sqrt{5})$
	* $V_v=\pi \cdot 4\cdot 5\cdot 8\cdot \sqrt{5}$
	* $V_v=1123.97cm^3$
	* ==$V_v=1.123dm^3=1.123L$==<br><br>
	* Ak sa uhlopriečka zdvojnásobí?
	* $|AC|'=40cm$
	* $5x^2=|AC|'\;^2$
	* $x^2=320$
	* $x=\sqrt{320}$
	* $x=8\sqrt{5}$<br><br>
	* $V_v=\pi (\frac{x}{2})^2\cdot 2x$
	* $V_v=\pi (\frac{8\sqrt{5}}{2})^2\cdot 2(8\sqrt{5})$
	* $V_v=\pi\cdot 16\cdot 5\cdot 16\sqrt{5}$
	* $V_v=8991.76$
	* ==$V_v=8.991dm^3=8.991L$==
	* Uhlopriečka sa zdvojnásobí = objem sa zosemnásobí $(2^3=8 - trojrozmerné\:teleso)$