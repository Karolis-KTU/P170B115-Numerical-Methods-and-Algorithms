# Netiesinių lygčių sprendimas
## 1 dalis (5 balai).
Išspręskite netiesines lygtis (1 ir 2 lentelės), kai lygties funkcija yra daugianaris f(x)=0 ir transcendentinė funkcija g(x)=0.
1. Nustatykite daugianario f(x) šaknų intervalą, taikydami "grubų" ir "tikslesnį" įverčius. Grafiškai pavaizduokite daugianarį tokiame intervale, kad matytusį abu įverčiai. Funkciją g(x) grafiškai pavaizduokite užduotyje nurodytame intervale. Esant poreikiui, grafikų ašis pakeiskite taip, kad būtų aiškiai matomos funkcijų šaknys;
2. Naudodami skenavimo algoritmą su nekintančiu skenavimo žingsniu raskite šaknų atskyrimo intervalus. Daugianariui skenavimo intervalas parenkamas pagal 1 užduoties punkte gautas įverčių reikšmes. Funkcija g(x) skenuojama užduotyje nurodytame intervale.
3. Skenavimo metodu atskirtas daugianario ir funkcijos šaknis tikslinkite užduotyje nurodytais metodais. Skaičiavimo scenarijuje turi būti panaudotos skaičiavimų pabaigos sąlygos. Skaičiavimų rezultatus pateikite lentelėje, kurioje nurodykite šaknies tikslinimui naudojamą metodą, tikslumą, iteracijų skaičių. Palyginkite, kuriuo metodu sprendimui rasti panaudota mažiau iteracijų.
4. Gautas šaknų reikšmes patikrinkite naudodami išteklius (funkcijas **roots** arba **fzero**, tinklalapį [www.wolframalpha.com](https://www.wolframalpha.com/) arba kitas priemones) ir pateikite patikrinimo rezultatus.

## 2 dalis (5 balai).
3 lentelėje pateikta funkcija h(x) išskleiskite Teiloro eilute (TE) nurodyto intervalo vidurio taško aplinkoje. Nustatykite TE narių skaičių, su kuriuo visos TE šaknys esančios nurodytame intervale, skiriasi nuo funkcijos h(x) šaknų ne daugiau negu |1e-4|. Tiek pateiktos funkcijos h(x) šaknis, tiek TE šaknis raskite antru iš pirmoje dalyje realizuotų metodų (Niutono arba Kvazi-Niutono, priklausomai nuo varianto). Darbo ataskaitoje pateikite:
1. tarpinius grafikus, kai drauge su pateikta funkcija h(x) nurodytame intervale atvaizduojama TE, kai jos narių skaičius lygus 3, 4 ir 5. 
2. graifką, kuriame pavaizduotas reikalaujamą tikslumą užtikrinantis pagal TE sudarytas daugianaris, drauge pateikiant ir funkcijos h(x) grafiką.
3. nustatytos reikalaujamą tikslumą užtikrinančios TE analitinę išraišką daugianario pavidalu.
4. grafikus, pagal kuriuos būtų galima įvertinti, kaip gerėjo sprendinys priklausomai nuo TE narių skaičiaus:
    - grafikas, kuris nurodo visą randamų šaknų skaičių nagrinėjamame intervale (ox-TE eilė, oy-šaknų skaičius);
    - atskiri grafikai kiekvienai šakniai, kuriuose oy ašyje pateikti tikslumo įveričiai tarp h(x) apskaičiuotos šaknies ir artimiausios TE šaknies, o o ašyje TE narių skaičiai.

## 1 lentelė. Netiesinių lygčių sprendimas. Metodai.
| Metodo nr. | Metodo pavadinimas        |
|------------|---------------------------|
| 1          | Stygų                     |
| 2          | Pusiaukirtos              |
| 3          | Niutuno (liestinių)       |
| 4          | Kvazi-Niutono (kirstinių) |

## 2 lentelė. Netiesinių lygčių sprendimas. Funkcijos ir metodai.
| Varianto Nr. | Daugianariai f(x) | Funkcijos g(x) | Metodai |
| --- | --- | --- | --- |
| 1 | $0.10x^5-0.05x^4-1.95x^3+1.75x^2+5.18x-2.14$ | $\frac{(x+1)^2(x-3)^2}{x^3+2}+(x-2)^3cos(x); 0 <= x <= 15$ | 2,3 |
| 2 | $−1.35x^4−0.93x^+26.46x^2+16.20x − 76.19$ | $\frac{ln(x)}{sin(2x) + 1.5}-\frac{x}{7}; 1 <= x <= 10$ | 1, 3 |
| 3 | $−0.45x^4+1.04X^3+1.42x^2−2.67x−0.97$ | $\frac{cos(2x)}{sin(x)+1,5}-\frac(x){5}; -5 <= x <= 5$ | 2, 4 |
| 4 | $−0.79x^4+6.17x^3−16.66x^2+17.91x−6.19$ | $2xcos(x) − (\frac{x}{2}+0.5)^3; −10<=x<=10$ | 1, 4 |
| 5 | $−1.29x^4+5.08x^3−2.76x^2−6.31x+4.10$ | $xcos^2(x)−(\frac{x}{2})^2; −10<=x<=10$ | 1, 3 |
| 6 | $-0.63x^4+3.92x^3-7.95x^2+5.50x-0.53$ | $sin(x)(x^2−1)(x+3)−0.9; −10<=x<=10$ | 1, 4 |
| 7 | $0.89x^4+0.07x^3−23.05x^2+4.03x+128.68$ | $e^{-x}\frac{cos(x)}{x-6}; -5<=x<=5$ | 1, 2 |
| 8 | $−0.67x^4+2.51x^3+2.27x^2−4.02x−2.48$ | $𝑒^{−x^2}sin(x2)(x+2); −3<=x<=3$ | 2, 4 |
| 9 | $0.48x^5+1.71x^4−0.67x^3−4.86x^2−1.33x+1.50$ | $e^{−x}sin(x^2)+0.001; 5<=x<=10$ | 2, 3 |
| 10 | $0.25x^5+0.68x^4−1.65x^3−5.26x^2−1.91x+1.36$ | $e^{−x}cos(x)sin(x^2−1); 7<=x<=8$ | 1, 4 |
| 11 | $−0.3x^5−1.10x^4+1.14x^3+3.84x^3+1.48x−0.22$ | $2−ln(x)sin(x^2); 6<=x<=9$ | 2, 4 |
| 12 | $0.16x^5−1.57x^4+4.38x^3−1.15x^2−6.29x+0.15$ | $2x sin(x)−(\frac{x}{2}+2)^2; -10<=x<=10$ | 2, 3 |
| 13 | $0.88x^4−1.44x^3−5.33x^2+7.35x+0.83$ | $1.9x sin(x)−(\frac{x}{1.5}-3)^2; −10<=x<=10$ | 1, 4 |
| 14 | $0.85x^4−9.92x^3+40.02x^2−64.68x+34.25$ | $cos(2x)𝑒^{-(\frac{x}{2})^2}; −6<=x<=6$ | 1, 2 |
| 15 | $2.19x^4−5.17x^3−7.17x^2+15.14x+1.21$ | $𝑒^{-(\frac{x}{2})^2}sin(2x); −6<=x<=6$ | 1, 3 |
| 16 | $−1.40x^4+0.23x^3+6.27x^2−1.14x−3.74$ | $(\frac{x}{2}+1.5)^2-xcos(2x); −10<=x<=10$ | 2, 4 |
| 17 | $1.03x^5−2.91x^4−1.44x^3+5.56x^2−0.36x−1.13$ | $sin(x)ln(x)−\frac{x}{6}; 1<=x<=20$ | 1, 3 |
| 18 | $−0.95x^4+10.19x^3−37.83x^2+55.58x−24.49$ | $sin^2(x)ln(x)−\frac{x}{4}; 1<=x<=10$ | 1, 4 |
| 19 | $−1.09x^4+1.89x^3+11.98x^2−19.84x−3.85$ | $cos(x)ln^2(x)+0.1; 0.1<=x<=10$ | 2, 3 |
| 20 | $1.34x^4−16.35x^3+65.13x^2−83.45x−3.27$ | $sin(x)−\frac{ln(x)}{2}+0.1; 0.1<=x<=10$ | 1, 3 |
| 21 | $−0.70x^4+4.16x^3+1.19x^2−33.40x+31.51$ | $e^{sin(x)}−\frac{x}{10}; 1<=x<=15$ | 1, 2 |
| 22 | $−0.82x^4+2.16x^3+10.27x^2−28.32x+14.85$ | $2e^{−(x−1)^2}+3sin(0.2x)-2; −3<=<=15$ | 1, 4 |
| 23 | $1.20x^4−11.84x^3+36.35x^2−34.77x+7.23$ | $\frac{(x−2)^2}{4}+5sin(x); −5<=x<=15$ | 2, 4 |
| 24 | $0.47x^4+1.86x^3−1.01x^2−6.39x−1.85$ | $e^x+x^{-x}−100sin^2(x); −1<=x<=6$ | 2, 3 |
| 25 | $−0.76x^4+3.30x^3+9.74x^2−34.58x−31.89$ | $\sqrt{x}sin(2x); 1<=x<=10$ | 1, 4 |
| 26 | $1.40x^5+0.85x^4−8.22x^3−4.67x^2+6.51x+0.86$ | $x^2sin(x)cos(x); 1<=x<=10$ | 1, 2 |
| 27 | $0.97x^5−4.45x^4+3.28x^3+6.09x^2−6.21x+0.46$ | $\frac{x}{3}+2\sqrt{(x^2+2)}sin(x); −1<=x<=15$ | 2, 3 |
| 28 | $0.67x^4−4.40x^3+2.69x^2+19.61x−16.29$ | $2xcos(x)−(\frac{x}{2}+0.5)^3; −10<=x<=10$ | 1, 3 |
| 29 | $−1.33x^4−2.93x^3+18.22x^2+9.70x−8.15$ | $xcos^2(x)−(\frac{x}{2})^2; −10<=x<=10$ | 2, 4 |
| 30 | $0.04x^4+0.06x^3−1.09x^2−1.09x+5.98$ | $sin(x)(x^2−1)(x+3)−0.9; −10<=x<=10$ | 1, 4 |

## 3 lentelė. Netiesinių lygčių sprendimas. Funkcijos h(x).
| Varianto Nr. | Funkcijos h(x) | Nagrinėjamas intervalas |
| --- | --- | --- |
| 1 | $90cos(x)+12−5x$ | $−10<=x<=0$ |
| 2 | $6sin(x)−cos(2x)+x$ | $−3<=x<=4$ |
| 3 | $−61cos(x)+cos(2x)+12$ | $1<=x<=6$ |
| 4 | $72sin(x)−9+2x$ | $−4<=x<=4$ |
| 5 | $29sin(x)−5cos(4x)$ | $0<=x<=4$ |
| 6 | $−2cos(x)+cos(4x)+2$ | $−2<=x<=2$ |
| 7 | $−54sin(x)−2+5x$ | $−5<=x<=6$ |
| 8 | $5cos(x)−cos(2x)+2$ | −6<=x<=3$ |
| 9 | $2cos(x)−47cos(2x)+2$ | −6<=x<=0$ |
| 10 | $−79cos(x)−11−4x$ | $−10<=x<=0$ |
| 11 | $−77sin(x)+25−3x$ | $−4<=x<=6$ |
| 12 | $−11sin(2x)+29cos(x)+x$ | $0<=x<=5$ |
| 13 | $−5cos(x)+72cos(4x)+2$ | $−4<=x<=−2$ |
| 14 | $14sin(x)+5x−12$ | $−5<=x<=7$ |
| 15 | $154sin(x)−9+2x^2$ | $−2<=x<=8$ |
| 16 | $9sin(x)−5sin(4x)$ | $−2<=x<=2$ |
| 17 | $−31sin(2x)+5cos(8x)$ | $0<=x<=2$ |
| 18 | $−111sin(x)+1+x^2$ | $−2<=x<=8$ |
| 19 | $9sin(x)−19cos(2x)+x$ | $0<=x<=5$ |
| 20 | $−8sin(x)+32sin(10x)−10$ | $0<=x<=1$ |
| 21 | $−2cos(x)+cos(4x)+2$ | $−2<=x<=2$ |
| 22 | $−55sin(x)−2+4x$ | $-5<=x<=6$ |
| 23 | $2cos(x)−cos(2x)+2$ | $−6<=x<=0$ |
| 24 | $cos(x)−47cos(3x)+2$ | $−6<=x<=3$ |
| 25 | $−75cos(x)−10−4x$ | $−10<=x<=0$ |
| 26 | $−72sin(x)+21−3x$ | $−4<=x<=6$ |
| 27 | $−12sin(2x)+19cos(x)+x$ | $0<=x<=5$ |
| 28 | $-6cos(x)+62cos(5x)+2$ | $−4<=x<=−2$ |
| 29 | $18sin(x)−11+4x$ | $−5<=x<=7$ |
| 30 | $134sin(x)−9+x^2$ | $−2<=x<=8$ |