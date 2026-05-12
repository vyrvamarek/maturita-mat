## Maturitné zadanie 25

### **1.** Definujte pojmy výrok, pravdivostná hodnota výroku, negácia výroku, zložený výrok, kvantifikovaný výrok. Vysvetlite pojmy: konjunkcia, disjunkcia, implikácia, ekvivalencia výrokov a uveďte príklady.

***Výrok** - Tvrdenie v tvare oznamovacej vety, o pravdivosti ktorého má zmysel uvažovať*
***Pravdivostná hodnota výroku**- údaj, ktorý určuje, či je výrok pravdivý alebo nepravdivý*
***Negácia výroku** - uprava výroku tak aby mal opačné pravdivostné hodnoty ako pôvodný výrok*
***Zložený výrok** - výrok ktorý vznikne spojením dvoch jednoduchých výrokov pomocou logických spojok*
***Kvantifikovaný výrok** - vyjadrujú počet alebo rozsah objektov pre ktoré platí určitá vlastnosť,*
*obsahujú kvantifikátory: ∀ (všetci, každý, ľubovoľný),  ∃ (existuje aspoň 1) | ∃! (existuje práve jeden)*

- *Konjunkcia ($A\land B$)*
    - *Zložený výrok, ktorý vznikne spojením dvoch alebo viacerých výrokov spojkou a; i; aj; a súčasne*
    - *"Mám veľa kamarátov a dobré známky."*
    - *Negácia: Inkluzívna disjunkcia znegovaného prvého a znegovaného druhého výroku -> (A'ÚB')*
- *Disjunkcia ($A\lor B$)
    - *Zložený výrok, ktorý vznikne spojením dvoch alebo viacerých výrokov spojkou alebo; či*
    - *"Mám ceruzku alebo pero."*
    - *Negácia: Konjunkcia znegovaného prvého a znegovaného druhého výroku -> (A'ÙB')*
    - *Ú -> alebo [inkluzívna disjunkcia]*
    - *Ú -> buď, alebo [exkluzívna disjunkcia]
- *Implikácia ($A=>B$)*
    - *Zložený výrok, ktorý vznikne spojením dvoch výrokov tak, že pred prvý výrok predradíme slovo "ak" a pred druhý predradíme slovo "tak" alebo nepredradíme nič*
    - *"Ak prší, tak je mokro."*
    - *Negácia: Konjunkcia prvého a znegovaného druhého výroku -> (AÙB')*
    - *Obrátená implikácia: implikácia druhého a prvého výroku*
    - *Obmena implikácie: implikácia znegovaného druhého a znegovaného prvého výroku (rovnaká pravdivostná hodnota ako originálna implikácia)*
- *Ekvivalencia ($A\cup B$) - obojstranná implikácia*
    - *Zložený výrok, ktorý vznikne spojením dvoch výrokov tak, že za prvý výrok priradíme slovné spojenie "vtedy a len vtedy/práve vtedy" a pred druhý predradíme slovo "keď"*
    - *"Jednotku z písomky dostanem práve vtedy, keď sa budem učiť."*
    - *Negácia: Inkluzívna disjunkcia konjunkcie prvého a znegovaného druhého výroku a konjunkcie druhého a znegovaného prvého výroku -> (AÙB') Ú (BÙA') | Exkluzívna disjunkcia prvého a druhého výroku -> (AÚB)*

### **2.** Dokážte, že ťažnica ľubovoľného trojuholníka je menšia, ako polovica jeho obvodu.

![[Pasted image 20260512194300.png]]

*Využijeme trojuholníkovú nerovnosť*

$b + \frac{a}{2} > t$
$c + \frac{a}{2} > t$
*Sčítame*
$b + \frac{a}{2} + \frac{a}{2} + c > 2t$
$b + a + c > 2t$
$o > 2t$
$\frac{o}{2} > t$

### **3.** Daná je kocka ABCDEFGH tak, že $A[2; 0; 0]$, $B[2; 2; 0]$, $C[0; 2; 0]$. Určte súradnice ostatných vrcholov kocky, vypočítajte:

![[IMG_20260513_003136925.jpg]]
### * vzdialenosť bodov S, D, ak S je stred úsečky AB

![[Pasted image 20260513003442.png]]
### * vzdialenosť bodu H od telesovej uhlopriečky, ktorá ním neprechádza.

![[IMG_20260513_003145954.jpg]]
### Ako sa zmenia súradnice vrcholov kocky, ak $A[0;0;0]$


![[IMG_20260513_003151721.jpg]]