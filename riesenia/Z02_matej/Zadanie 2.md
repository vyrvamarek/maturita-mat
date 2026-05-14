**1.** Definujte základné pojmy štatistiky: štatistický súbor, štatistický znak, absolútna a relatívna početnosť, modus, medián, rozptyl a diagram. Vysvetlite na príkladoch.

* Konkrétna pomôcka: Diagramy

**2.** Využitím vlastností súhlasných, striedavých alebo vrcholových uhlov dokážte, že:

* súčet veľkostí vnútorných uhlov trojuholníka je 180°
* trojuholník MBC je rovnoramenný, pričom bod M je priesečník priamky AB a rovnobežky s osou uhla β vedenej vrcholom C v ľubovoľnom trojuholníku ABC


**3.** Daná je funkcia $$f:y={-x}^2+4x-3$$
* načrtnite grafy funkcií $f(x),|f(x)|$
* určte pre všetky $r\in R$ , pre ktoré má rovnica $|f(x)| = r$ práve 4 riešenia
* ako je potrebné zmeniť číslo -3 v predpise funkcie $f$, aby graf funkcie prechádzal bodom $[0;2]$

_________________________________________________________________________

**TEÓRIA**
**Štatistický súbor:** 
- množina prvkov, ktorých vlastnosti skúmame 
- príklad: v grafe B je to 33 študentov

**Štatistický prvok/jednotka:** 
- jeden prvok štatistického súboru, na ktorom sa skúmajú chcené vlastnosti 
- príklad: v grafe B je to jeden študent

**Štatistický znak:** 
- vlastnosť, ktorú skúmame
1. kvalitatívny -> vlastnosti nevyjadriteľné číslom (farba niečoho) 
2. kvantitatívny -> dá sa číselne vyjadriť (číslo topánok, vek...) 
- príklad: v grafe B je to "počet dní v rodine"

**Početnosť znaku:** 
1. absolútna -> udáva presný počet štatistických jednotiek spĺňa daný znak 
príklad v grafe B:
(počet detí v rodine) - (absolútna početnosť)
1 - 6
2 - 13
3 - 9
4 - 1
5 - 2
6 - 2
2. relatívna -> pomer medzi absolútnou početnosťou daného znaku a rozsahom súboru 
príklad v grafe B:
(počet detí v rodine) - (relatívna početnosť)
1 - $\frac{6}{33} \approx 18,2\%$
2 - $\frac{13}{33} \approx 39,4\%$
3 - $\frac{9}{33} \approx 27,3\%$
4 - $\frac{1}{33} \approx 3,0\%$
5 - $\frac{2}{33} \approx 6,1\%$
6 - $\frac{2}{33} \approx 6,1\%$

**Modus:** 
- najčastejšie opakujúca sa hodnota súboru 
- príklad: v grafe B je to 2 (počet detí v rodine)

**Medián:** 
- stredná hodnota súboru (zoradenie vzostupne, tá v strede, ak nie je stred, tak priemer) 
- príklad: v grafe B je to 2 (počet detí v rodine)
- stredná hodnota v 33 je $\frac{33+1}{2}=17$ -> znak 17. jednotky -> $2$

**Rozptyl:** 
- stredná kvadratická odchýlka 
- určuje ako sú namerané hodnoty rozptýlené okolo ich aritmetického priemeru
$$d = \frac{1}{n}\sum_{i=1}^{n}{(\bar{x}-x_{i})^2}$$
$$\bar{x} = \frac{1\cdot6+2\cdot13+3\cdot9+4\cdot1+5\cdot2+6\cdot2}{33} = \frac{85}{33}$$
$$  
d=\frac{6(1-\frac{85}{33})^2+13(2-\frac{85}{33})^2+9(3-\frac{85}{33})^2+1(4-\frac{85}{33})^2+2(5-\frac{85}{33})^2+2(6-\frac{85}{33})^2}{33} = \approx 1.76$$
Diagram:
- vizuálne znázornenie štatistických súborov
- histogram - graf B
- polygón - graf C
- kruhový - graf A

![[Statistika.jpeg]]
**DÔKAZ**
a)
![[180_stupnov.svg]]
$AB // GF$
1. možnosť
$\alpha = \alpha'$ -> súhlasné uhly
$\beta = \beta'$ -> súhlasné uhly
$\gamma = \gamma'$ -> vrcholové uhly
$\alpha' + \beta' + \gamma' = 180 \degree \implies \alpha + \beta + \gamma = 180 \degree$ -> $\alpha'; \beta'; \gamma'$ tvoria priamy uhol na priamke GF
2. možnosť
$\alpha = \alpha''$ -> striedavé uhly
$\beta = \beta''$ -> striedavé uhly
$\alpha'' + \beta'' + \gamma = 180 \degree \implies \alpha + \beta + \gamma = 180 \degree$ -> $\alpha''; \beta''; \gamma$ tvoria priamy uhol na priamke GF

b)
![[MBC.svg]]
os uhla $\beta$ -> $o_{\beta}$ rozdelí uhol $\beta$ na 2 rovnaké uhly: $ε$ a $ε_{1}$
$ε_{1} = ε_{1}'$ -> striedavé uhly
$ε = ε'$ -> súhlasné uhly
čo znamená, že $ε' = ε_{1}'$ a teda v $\triangle MBC$ sú pri základni rovnaké uhly, preto proti nim ležia rovnako dlhé strany $\implies$ $\triangle MBC$ je rovnoramenný

**PRÍKLAD**
$f:y={-x}^2+4x-3$
a)
$y={-x}^2+4x-3$ -> rozloženie na štvorec aby som zistil priesečníky s osou x
$y=(x-1)(3-x)$ $\implies$ $Px_{1} [1;0]; Px_{2} [3;0]$
$Py [0;-3]$
$y={-0}^2+4.0-3$
$y = -3$

vieme zistiť aj vrchol paraboly -> priemer x súradníc priesečníkov a dopočítame y
$V [2;1]$
$y={-x}^2+4x-3$
$y={-2}^2+4.2-3$
$y=-4+8-3$
$y=1$

keďže pri ${-x}^2$ je $-$, tak to bude "smutná parabola"
![[f1.svg]]

$f_{1}:y=|{-x}^2+4x-3|$
kvôli absolútnej hodnote, sa celá časť pod osou x presunie nad os x
priesečníky s x aj vrchol ostávajú, keďže sú v kladnej časti osy y
zmení sa len $Py$
$Py [0;3]$
$y=|{0}^2+4.0-3|$
$y = |-3|$
$y = 3$

![[f2.svg]]
b)
rovnica $f_{1}:y=|{-x}^2+4x-3|$ má práve 4 riešenia na intervale: $y \in (0;1)$

c)
$f:y={-x}^2+4x-3$ -> $Py [0;-3]$
keďže to "-3" v predpise posúva funkciu v smere osi y (hore/dole), tak potrebujeme, aby $Py$ bol v bode $[0;2]$
rozdiel y súradníc => $2-(-3)=5$
k "-3" v predpise pripočítame 5, aby sa teda posunula o 5 hore
$f_{2}:y={-x}^2+4x+2$
![[f3.svg]]

