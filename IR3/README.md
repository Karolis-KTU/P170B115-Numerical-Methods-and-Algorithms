# Interpoliavimas, proksimavimas

## 1 Užduotis. Interpoliavimas daugianariu.
**1 lentelėje** duota interpoliuojamos funkcijos analitinė išraiška. Pateikite interpoliacinės funkcijos išraišką naudodami **1 lentelėje** nurodytas funkcijas, kai:
* Taškai pasiskirstę tolygiai.
* Taškai apskaičiuojami naudojant Čiobyševo abscises.

Interpoliavimo taškų skaičių parinkite laisvai, bet jis turėtų neviršyti 30. Pateikite du grafikus, kai interpoliuojančioss funkcijos apskaičiuojamos naudojant skirtingas abscises ir gautas interpoliuojančių funkcijų išraiškas. Tame pačiame grafike vaizduokite duotąją funkciją, interpoliuojančią funkciją ir netiktį.

## 2 Užduotis. Interpoliavimas splainu per duotus taškus
Sudarykite **2 lentelėje** nurodytos šalies 1998-2018 metų šiltnamio dujų emisiją (galimo duomenų šaltinio nuorada apačioje) interpoliuojančias kreives, kai interpoliuojama **2 lentelėje** nurodyto tipo splainu. Pateikite rezultatų grafiką (interpoliavimo mazgus ir gautą kreivę (vaizdavimo taškų privalo būti daugiau nei interpoliavimo mazgų)).

## 3 Užduotis. Aproksimavimas
Mažiausių kvadratų metodu sudarykite **2 lentelėje** nurodytos šalies 1998-2018 metų šiltnamio dujų emisiją (galimo duomenų šaltinio nuorada apačioje) aproksimuojančias kreives (**pirmos, antros, trečios** ir **penktos** eilės daugianarius). Pateikite gautas daugianarių išraiškas ir grafinius rezultatus.

## 4 Užduotis. Parametrinis aproksimavimas.
Naudodami **parametrinį aproksimavimą Haro bangelėmis** suformuoktie **2 lentelėje** nurodytos šalies kontūrą. Analizuokite bent 10 detalumo lygių. Pateikite aproksimavimo rezultatus (aproksimuotą kontūro kreivę) ne mažiau kaip 4 skirtinguose lygmenyse. Jei šalis turi keletą atskirų teritorijų (pvz., salų), pakanka analizuoti didžiausią iš jų.

## **1 lentelė.** Interpoliuojamos funkcijos išraiška
| **Var. Nr.** | **Funkcijos išraiška** | **Bazinė funkcija** |
|---|---|---|
| 1 | $e^{-x^2}*sin(x^2)*(x-3); -3 \leq x \leq 2$ | Čiobyševo |
| 2 | $\frac{ln(x)}{(sin(2*x)+1,5)}+x/5; 2 \leq x \leq 10$ | Vienanarių |
| 3 | $e^{-x^2}*cos(x^2)*(x-3); -3 \leq x \leq 2$ | Čiobyševo |
| 4 | $cos(2*x)*(sin(2*x)+1,5)+cosx; -2 \leq x \leq 3$ | Vienanarių |
| 5 | $e^{-x^2}*sin(x^2)*(x-3); -3 \leq x \leq 2$ | Čiobyševo |
| 6 | $\frac{ln(x)}{(sin(2*x)+1,5)}+x/5; 2 \leq x \leq 10$ | Vienanarių |
| 7 | $cos(2*x)*(sin(2*x)+1,5)+cos\frac{x}{5}; -2 \leq x \leq 3$ | Čiobyševo |
| 8 | $\frac{ln(x)}{(sin(2*x)+1,5)}+x/5; 2 \leq x \leq 10$ | Vienanarių |
| 9 | $cos(2*x)*(sin(2*x)+1,5)+cosx; -2 \leq x \leq 3$ | Čiobyševo |
| 10 | $cos(2*x)*(sin(3*x)+1,5)+cos\frac{x}{5}; -2 \leq x \leq 3$ | Vienanarių |

## **2 lentelė.** Šalys ir splaino tipas interpoliavimui.
| **Var. Nr.** | **Šalis** | **Splainas** |
|---|---|---|
| 1 | Argentina | Globalus |
| 2 | Prancūzija | Ermito (Akima) |
| 3 | Ispanija | Globalus |
| 4 | Latvija | Ermito (Akima) |
| 5 | Kroatinija | Globalus |
| 6 | Malis | Ermito (Akima) |
| 7 | Venesuela | Globalus |
| 8 | Austrija | Ermito (Akima) |
| 9 | Panama | Globalus |
| 10 | Zambija | Ermito (Akima) |

## Galimas duomenų šaltinis:
Šiltnamio dujų emisijos duomenys:
https://data.worldbank.org/indicator/EN.ATM.GHGT.KT.CE?end=2018&start=1998

Šalių kontūrai:
http://www.naturalearthdata.com/downloads/10m-cultural-vectors/