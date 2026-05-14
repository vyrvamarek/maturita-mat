## Maturitné zadanie 16

**1.** Využitím jednotkovej kružnice definujte funkcie kosínus a tangens. Načrtnite ich grafy, určte na akých množinách sú tieto funkcie definované a popíšte, ktoré z nasledujúcich vlastností každá funkcia spĺňa: či je prostá, monotónna, má maximum, alebo minimum, je ohraničená párna alebo nepárna.

**2.** Dokážte Pytagorovu vetu.

**3.** V obchodnom dome majú zo 100 televízorov 85 bezchybných a 15 televízorov so skrytou vadou. Ak prvých desať kupujúcich dostalo bezchybný televízor, aká je pravdepodobnosť, že jedenástemu predajú televízor so skrytou vadou? Ako by sa zmenila situácia, keby prvých 10 kupujúcich dostalo chybný televízor?

---

1. Teória
	* <iframe src="https://phet.colorado.edu/sims/html/trig-tour/latest/trig-tour_all.html?locale=sk"width="100%" height="500px"></iframe>
	* V karteziánskej sústave v rovine si môžeme zadefinovať jednotkovú kružnicu $k$. Jej stred leží na počiatku súradnicovej sústavy, v bode $S[0;0]$. Rovnica tejto kružnice bude potom $x^2+y^2=1$. <br><br>
	* **Kosínus** uhla $\alpha$ je $x$-ová (v znázornení modrá) súradnica priesečníka ramena uhla $\alpha$ s jednotkovou kružnicou v karteziánskej sústave<br>
		* Vo vizualizácii - hodnota $cos\alpha$ sa pohybuje od -1 po 1, podľa pohybu po $x$-ovej súradnici na súradnicovej sústave<br>
		* ![[/riesenia/svg/U16cos.svg|350]]
		* $f(x):y=\cos x$
			* $D(f)=R$
			* $H(f)=\langle 1;-1\rangle$
			* Párna funkcia
				* $\forall x\in R:\cos(-x)=\cos(x)$
				* Kosínusoida je osovo súmerná podĺa osi y
			* Periodickosť
				* Perióda $T=2\pi$
				* Platí: $cos(x)=cos(x+2k\pi)$
			* Ohraničenosť
				* Je ohraničená zhora (1)
				* Je ohraničená zdola (-1)
				* = je ohraničená
			* Nieje prostá (iba na zúženom $D=\langle 0;\pi\rangle$)
			* Monotónnosť
				* Nieje monotónna na celom $D(f)$
				* Prísne rastúca na intervale $\langle2k\pi+\pi;\:2k\pi+2\pi\rangle$
				* Prísne klesajúca na intervale $\langle2k\pi;\:2k\pi+\pi\rangle$
			* Extrémy
				* Dosahuje maximum: hodnota $y=1$; v bodoch $x=2k\pi,\;\forall k\in Z$
				* Dosahuje minimum: hodnota $y=-1$; v bodoch $x=2k\pi+\pi,\;\forall k\in Z$<br><br>
	* **Tangens** uhla $\alpha$ je pomer $y$ a $x$ ($\frac{y}{x}$) súradníc priesečníka ramena uhla $\alpha$ s jednotkovou kružnicou. Je definovaný ako pomer $\frac{\sin x}{\cos x}$<br>
		* Vo vizualizácii - pomer sa podľa pohybbru okolo kružnice mení. V bodoch kde $cos x$ dosiahne hodnotu 0, nemôže platiť pomer $\frac{y}{x}\;teda\;\frac{\sin x}{\cos x}$, keďže 0 deliť nevieme. Preto sú v týchto hodnotách asymptoty funkcie tangens<br>
		* ![[/riesenia/svg/U16tan.svg|350]]
		*  $f(x):y=\tan x$
			* $D(f)=R-\{\frac{\pi}{2}+k\pi \}$
			* $H(f)=R$
			* Nepárna
				* $\forall x\in R:\tan(-x)=-\tan(x)$
				* Tangentoida je stredovo súmerná podľa bodu $[0;0]$
			* Periodickosť
				* perióda $T=\pi$
				* platí: $tan(x)=tan(x+k\pi)$
			* Nieje ohraničená (nieje ohraničená zdola, zhora = nieje ohraničená)
			* Nieje prostá (iba na zúženom $D=(-\frac{\pi}{2};\;\frac{\pi}{2})$)
			* Monotónnosť
				* Nieje monotónna na celom $D(f)$
				* Prísne rastúca na intervale $(D=(-\frac{\pi}{2}+k\pi;\;\frac{\pi}{2}+k\pi))$
			* Extrémy nedosahuje (ani minimum, ani maximum)
2. Dôkaz
	$$a^2+b^2=c^2$$
	![[/riesenia/svg/U16euklid.jpeg]]
	![[/riesenia/svg/U16pito.jpeg]]
	* hore je baškine vypracovanie (ako sme robili na hodine pomocou euklidovych viet)<br><br>
	* moje vypracovanie:
		* $\square ABCD$
		* $|AB|=|BC|=|CD|=|DA|=a+b$
		* $a<b$
		* $E, F, G, H;\;E\in|AB|;F\in|BC|...;\;|AE|>|EB|\land |AE|=|BF|$
		* $\triangle EBF\cong\triangle FCG\cong\triangle GDH\cong\triangle HAE$
		* $\angle FEB=\alpha;\;\angle EFB=\beta$
		* $\alpha+\beta+90\degree=180\degree$
		* $\alpha+\beta=90\degree\;\rightarrow\angle EFG=90\degree\;\rightarrow\square EFGM=štvorec$
		* $\square ABCD=\square 1;\;\square EFGH=\square 2;\;\triangle EBF=\triangle 1$<br><br>
		* ![[/riesenia/svg/U16pitomarek.jpg|400]]<br><br>
		* Sústava rovníc<br><br>
			* I. $S_{\square 1}=|AB|^2$
			* II.$S_{\square 1}=S_{\square 2}+4\cdot S_{\triangle 1}$
			  
			 ------------------------------------
			* I. $S_{\square 1}=(a+b)^2$
			* II. $S_{\square 1}=c^2+4\cdot \frac{a\cdot b}{2}$
			  
			 ------------------------------------
			*  I. $S_{\square 1}=a^2+2ab+b^2$
			* II. $S_{\square 1}=c^2+2ab$
			  $\downarrow$
			* $a^2+b^2+2ab=c^2+2ab$
			* ==$a^2+b^2=c^2$==
			* ČBTD
3. Príklad
	* $T=100$
	* $T_b=85$
	* $T_v=15$<br><br>
	* $T_b-10\Longrightarrow P(T_v)?$
	* $P(T_v)=\frac{T_v}{T-10}$
	* $P(T_v)=\frac{15}{90}$
	* $P(T_v)=0.1\overline{6}$<br><br>
	* $T_v-10\Longrightarrow P(T_v)$
	* $P(T_v)=\frac{T_v-10}{T-10}$
	* $P(T_v)=\frac{5}{90}$
	* $P(T_v)=0.0\overline{5}$
	  
	* Pravdepodobnosť toho, že v prípade a) si zákazník vyberie pokazený televízor je $0.1\overline 6$, zatiaľ čo v prípade b) $0.0\overline 5$.