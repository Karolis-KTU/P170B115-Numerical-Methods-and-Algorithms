# Lygčių sistemų sprendimas ir optimizavimas
## 1 Tiesinių lygčių sistemų sprendimas
- Lentelėje 1 duotos tiesinės lygčių sistemos, 2 lentelėje nurodyti metodai ir lygčių sistemų numeriai (iš 1 lentelės). Reikia suprogramuoti nurodytus metodus ir jais išspręsti pateiktas lygčių sistemas.
- Lentelėje 3 duotos tiesinės lygčių sistemos, laisvųjų narių vektoriai ir nurodytas skaidos metodas. Reikia suprogramuoti nurodytą metodą ir juo išspręsti pateiktas lygčių sistemas.

Sprendžiant lygčių sistemas (a ir b punktuose), turi būti:
- Programoje turi būti įvertinti atvejai:
    - kai lygčių sistema turi vieną sprendinį;
    - kai lygčių sistema sprendinių neturi;
    - kai lygčių sistema turi be galo daug sprendinių.
- Patikrinkite gautus sprendinius ir skaidas, įrašydami juos į pradinę lygčių sistemą.
- Gautą sprendinį patikrinkite naudodami išorinius išteklius (pvz., standartines Python funkcijas).

## 2 Netiesinių lygčių sistemų sprendimas
Duota netiesinių lygčių sistema (4 lentelė):
$$ \begin{cases} Z_1(x_1, x_2) = 0 \\ Z_2(x_1, x_2) = 0 \end{cases} $$

- Skirtinguose grafikuose pavaizduokite paviršius $Z_1(x_1, x_2)$ ir $Z_2(x_1, x_2)$.
- Užduotyje pateiktą netiesinių lygčių sistemą išspręskite grafiniu būdu.
- Nagrinėjamoje srityje sudarykite stačiakampį tinklelį ($x_1$, $x_2$ poras). Naudodami užduotyje nurodytą metodą apskaičiuokite netiesinių lygčių sistemos sprendinius, kai pradinis artinys įgyja tinklelio koordinačių reikšmes. Tinklelyje vienodai pažymėkite taškus, kuriuos naudojant kaip pradinius artinius gaunamas tas pats sprendinys. Lentelėje pateikite apskaičiuotus skirtingus sistemos sprendinius ir bent po vieną jam atitinkantį pradinį artinį.
- Gautus sprendinius patikrinkite naudodami išorinius išteklius (pvz., standartines Python funkcijas).

## 3 Optimizavimas
Pagal pateiktą uždavinio sąlygą (5 lentelė) sudarykite tikslo funkciją ir išspręskite jį vienu iš gradientinių metodų (gradientiniu, greičiausio nusileidimo). Guatą taškų konfigūraciją pavaizduokite programoje, skirtingais ženklais pavaizduokite duotus ir pridėtus (jei sąlygoje tokių yra) taškus. Ataskaitoje pateikite pradinę ir gautą taškų konfigūracijas, taikytos tikslo funkcijos aprašymą, taikyto metodo pavadinimą ir parametrus, iteracijų skaičių, iteracijų pabaigos sąlygas ir tikslo funkcijos priklausomybės nuo iteracijų skaičiaus grafiką.

## 1 lentelė. Lygčių sistemos.
| Nr. | Lygčių sistema |
| --- | --- |
| 1 | $\begin{cases} 3x_1 + 7x_2 + x_3 + 3x_4 = 37 \\ x_1 - 6x_2 + 6x_3 + 9x_4 = 11 \\ 4x_1 + 4x_2 - 7x_3 + x_4 = 38 \\ -3x_1 + 8x_2 + 2x_3 + x_4 = 0 \end{cases}$ |
| 2 | $\begin{cases} 3x_1 + 10x_2 + x_3 + 5x_4 = 83 \\ -2x_1 - 6x_2 + 12x_3 + 14x_4 = 178 \\ 3x_1 + 12x_2 - 5x_3 + x_4 = 37 \\ -3x_1 - 9x_2 + 5x_3 = -26 \end{cases}$ |
| 3 | $\begin{cases} 3x_1 + 7x_2 + x_3 + 3x_4 = 40 \\ x_1 - 6x_2 + 6x_3 + 8x_4 = 19 \\ 4x_1 + 4x_2 - 7x_3 + x_4 = 36 \\ 4x_1 + 16x_2 + 2x_3 = 48 \end{cases}$ |
| 4 | $\begin{cases} 9x_1 + x_2 - 2x_3 + x_4 = 47 \\ 11x_2 + 3x_3 + 4x_4 = -24 \\ x_1 + 3x_2 + 12x_3 - 3x_4 = 27 \\ -x_2 + 2x_3 + 2x_4 = -5 \end{cases}$ |
| 5 | $\begin{cases} 4x_1 + 12x_2 + x_3 + 7x_4 = 171 \\ 2x_1 + 6x_2 + 17x_3 + 2x_4 = 75 \\ 2x_1 + x_2 + 5x_3 + x_4 = 30 \\ 5x_1 + 11x_2 + 7x_3 = 50 \end{cases}$ |
| 6 | $\begin{cases} 4x_1 + x_2 + x_3 + 7x_4 = 148 \\ x_1 + 2x_3 - 2x_4 = -37 \\ 2x_1 + 2x_2 - 7x_3 + x_4 = 21 \\ 4x_1 + 14x_2 + 7x_3 = 53 \end{cases}$ |
| 7 | $\begin{cases} 5x_1 + x_2 + 3x_3 - x_4 = -5 \\ x_1 + 4x_2 + 2x_4 = 3 \\ 3x_1 + 11x_3 - 5x_4 = -4 \\ -x_1 + 2x_2 + 5x_3 + 2x_4 = -7 \end{cases}$ |
| 8 | $\begin{cases} 4x_1 + 3x_2 - x_3 + x_4 = 12 \\ 3x_1 + 9x_2 - 2x_3 - 2x_4 = 10 \\ -x_1 - 2x_2 + 11x_3 - x_4 = -28 \\ x_1 - 2x_2 - x_3 + 5x_4 = 16 \end{cases}$ |
| 9 | $\begin{cases} x_2 + 2x_3 + x_4 = 2 \\ 6x_1 - 2x_2 + 3x_3 + 4x_4 = -15 \\ 3x_2 + 4x_3 - 3x_4 = 10 \\ -4x_2 + 3x_3 + x_4 = -2 \end{cases}$ |
| 10 | $\begin{cases} 9x_1 + 3x_2 - x_3 + 2x_4 = 65 \\ 3x_1 + 11x_2 - 2x_3 - 2x_4 = 27 \\ -x_1 - 2x_2 + 6x_3 - x_4 = -23 \\ 2x_1 -2x_2 - x_3 + 9x_4 = 39 \end{cases}$ |
| 11 | $\begin{cases} 2x_1 + 5x_2 + x_3 + 2x_4 = 14 \\ -2x_1 + 3x_3 + 5x_4 = 10 \\ x_1 - x_3 + x_4 = 4 \\ 5x_2 + 4x_3 + 7x_4 = 24 \end{cases}$ |
| 12 | $\begin{cases} 3x_1 + x_2 - x_3 + 5x_4 = 20 \\ -3x_1 + 4x_2 - 8x_3 - x_4 = -36 \\ x_1 - 3x_2 + 7x_3 + 6x_4 = 41 \\ 5x_2 - 9x_3 + 4x_4 = -16 \end{cases}$ |
| 13 | $\begin{cases} x_1 - 2x_2 + 3x_3 + 4x_4 = 11 \\ x_1 - x_3 + x_4 = -4 \\ 2x_1 - 2x_2 + 2x_3 + 5x_4 = 7 \\ -7x_2 + 3x_3 + x_4 = 2 \end{cases}$ |
| 14 | $\begin{cases} 2x_1 + 4x_2 + 6x_3 - 2x_4 = 4 \\ x_1 + 3x_2 + x_3 - 3x_4 = -7 \\ x_1 + x_2 + 5x_3 + x_4 = 11 \\ 2x_1 + 3x_2 - 3x_3 - 2x_4 = -4 \end{cases}$ |
| 15 | $\begin{cases} -4x_1 + 3x_2 - 5x_3 + 5x_4 = -4 \\ 2x_1 + 2x_2 + 4x_3 + 3x_4 = 16 \\ -7x_2 + 2x_3 - 5x_4 = 9 \\ x_1 + x_2 + 2x_3 + x_4 = 8 \end{cases}$ |
| 16 | $\begin{cases} x_1 + 2x_2 + x_3 + x_4 = -7 \\ 2x_1 - 5x_2 + x_3 + 2x_4 = 3 \\ 4x_1 - x_2 + 3x_3 + 4x_4 = 0 \\ 3x_1 - 3x_2 + 2x_3 + 3x_4 = 2 \end{cases}$ |
| 17 | $\begin{cases} 2x_1 + 5x_2 + x_3 + 2x_4 = -1 \\ -2x_1 + 3x_3 + 5x_4 = 7 \\ x_1 - x_3 + x_4 = 3 \\ 5x_2 + 4x_3 + 7x_4 = 4 \end{cases}$ |
| 18 | $\begin{cases} x_1 + 2x_2 + x_3 = -4 \\ 2x_1 + 5x_2 + 4x_4 = 3 \\ 14x_1 - 8x_2 + 4x_3 + x_4 = 7 \\ 4x_1 + 10x_2 + 8x_4 = 2 \end{cases}$ |
| 19 | $\begin{cases} 3x_1 + x_2 - x_3 + 5x_4 = 8 \\ -3x_1 + 4x_2 + 8x_3 - x_4 = 10 \\ x_1 - 3x_2 + 7x_3 + 6x_4 = 11 \\ 5x_2 - 9x_3 + 4x_4 = 1 \end{cases}$ |
| 20 | $\begin{cases} 2x_1 + 4x_2 + 6x_3 - 2x_4 = 2 \\ x_1 + 3x_2 + x_3 - 3x_4 = 1 \\ x_1 + x_2 + 5x_3 + x_4 = 7 \\ 2x_1 + 3x_2 - 3x_3 - 2x_4 = 2 \end{cases}$ |

## 2 lentelė. Tiesinių lygčių sistemų metodai ir lygčių sistemų Nr.
<table>
    <thead>
        <tr>
            <th>Užduoties Nr.</th>
            <th>Metodas</th>
            <th>Lygčių sistemos Nr. (1 lentelė)</th>
        </tr>
    <thead>
    <tbody>
        <tr>
            <td rowspan=2>1</td>
            <td>Gauso</td>
            <td>10, 11, 17</td>
        </tr>
        <tr>
            <td>Paprastųjų iteracijų</td>
            <td>10</td>
        </tr>
        <tr>
            <td rowspan=2>2</td>
            <td>Gauso</td>
            <td>9, 15, 18</td>
        </tr>
        <tr>
            <td>Gauso-Zeidelio</td>
            <td>9</td>
        </tr>
        <tr>
            <td rowspan=2>3</td>
            <td>Atspindžio</td>
            <td>7, 15, 16</td>
        </tr>
        <tr>
            <td>Paprastųjų iteracijų</td>
            <td>7</td>
        </tr>
        <tr>
            <td rowspan=2>4</td>
            <td>Atspindžio</td>
            <td>3, 12, 19</td>
        </tr>
        <tr>
            <td>Gauso-Zeidelio</td>
            <td>3</td>
        </tr>
        <tr>
            <td rowspan=2>5</td>
            <td>Gauso</td>
            <td>2, 12, 17</td>
        </tr>
        <tr>
            <td>Paprastųjų iteracijų</td>
            <td>2</td>
        </tr>
        <tr>
            <td rowspan=2>6</td>
            <td>Gauso</td>
            <td>6, 15, 18</td>
        </tr>
        <tr>
            <td>Gauso-Zeidelio</td>
            <td>6</td>
        </tr>
        <tr>
            <td rowspan=2>7</td>
            <td>Atspindžio</td>
            <td>4, 14, 16</td>
        </tr>
        <tr>
            <td>Paprastųjų iteracijų</td>
            <td>4</td>
        </tr>
        <tr>
            <td rowspan=2>8</td>
            <td>Atspindžio</td>
            <td>1, 14, 20</td>
        </tr>
        <tr>
            <td>Gauso-Zeidelio</td>
            <td>1</td>
        </tr>
        <tr>
            <td rowspan=2>9</td>
            <td>Gauso</td>
            <td>5, 13, 19</td>
        </tr>
        <tr>
            <td>Gauso-Zeidelio</td>
            <td>5</td>
        </tr>
        <tr>
            <td rowspan=2>10</td>
            <td>Atspindžio</td>
            <td>8, 13, 20</td>
        </tr>
        <tr>
            <td>Paprastųjų iteracijų</td>
            <td>8</td>
        </tr>
    </tbody>
</table>

## 3 lentelė. Tiesinių lygčių sistemos ir laisvųjų narių stulpeliai.
| Užduoties Nr. | Lygčių sistema | b1 | B2 | B3 | Metodas |
| --- | --- | --- | --- | --- | --- |
| 1 | $\begin{cases} 2x_1+5x_2+x_3+2x_4=... \\ -2x_1+3x_3+5x_4=... \\ x_1-x_3+x_4=... \\ -3x_1-4x_2+x_3+x_4=... \end{cases}$ | $\begin{cases} ...=10 \\ ...=6 \\ ...=1 \\ ...=-5 \end{cases}$ | $\begin{cases} ...=74 \\ ...=28 \\ ...=18 \\ ...=-48 \end{cases}$ | $\begin{cases} ...=-0.25 \\ ...=-1 \\ ...=0.5 \\ ...=-0.5 \end{cases}$ | QR |
| 2 | $\begin{cases} x_1+2x_2+x_3=... \\ 2x_1+5x_2+4x_4=... \\ 14x_1-8x_3+4x_3+x_4=... \\ 5x_1-15x_2+3x_3=... \end{cases}$ | $\begin{cases} ...=4 \\ ...=11 \\ ...=11 \\ ...=23 \end{cases}$ | $\begin{cases} ...=20 \\ ...=75 \\ ...=16 \\ ...=149 \end{cases}$ | $\begin{cases} ...=-6 \\ ...=-16.75 \\ ...=23.25 \\ ...=-32.75 \end{cases}$ | QR |
| 3 | $\begin{cases} 3x_1+7x_2+x_3+3x_4=... \\ x_1-6x_2+6x_3+8x_4=... \\ 4x_1+4x_2-7x_3+x_4=... \\ -4x_1-3x_2+8x_3+2x_4=... \end{cases}$ | $\begin{cases} ...=14 \\ ...=9 \\ ...=2 \\ ...=9 \end{cases}$ | $\begin{cases} ...=78 \\ ...=-7 \\ ...=44 \\ ...=13 \end{cases}$ | $\begin{cases} ...=5.75 \\ ...=-9.25 \\ ...=6.5 \\ ...=0 \end{cases}$ | LU |
| 4 | $\begin{cases} x_1+2x_2+x_3+x_4=... \\ 2x_1-5x_2+2x_4=... \\ 9x_1-6x_2+6x_3+x_4=... \\ 5x_1-2x_2+x_4=... \end{cases}$ | $\begin{cases} ...=5 \\ ...=-1 \\ ...=-2 \\ ...=8 \end{cases}$ | $\begin{cases} ...=28 \\ ...=-22 \\ ...=-33 \\ ...=37 \end{cases}$ | $\begin{cases} ...=2.75 \\ ...=-3.25 \\ ...=-8.25 \\ ...=2.75 \end{cases}$ | LU |
| 5 | $\begin{cases} 4x_1+3x_2-x_3+x_4=... \\ 3x_1+9x_2-2x_3-2x_4=... \\ -x_1-2x_2+11x_3+x_4=... \\ x_1-2x_2-x_3+5x_4=... \end{cases}$ | $\begin{cases} ...=7 \\ ...=8 \\ ...=7 \\ ...=3 \end{cases}$ | $\begin{cases} ...=20 \\ ...=0 \\ ...=18 \\ ...=40 \end{cases}$ | $\begin{cases} ...=1 \\ ...=4 \\ ...=-10 \\ ...=3.5 \end{cases}$ | QR |
| 6 | $\begin{cases} 2x_1+x_2+x_3+x_4=... \\ x_1+3x_2+x_3-3x_4=... \\ x_1+x_2+5x_3+x_4=... \\ 2x_1-3x_2-3x_3-2x_4=... \end{cases}$ | $\begin{cases} ...=5 \\ ...=2 \\ ...=8 \\ ...=0 \end{cases}$ | $\begin{cases} ...=20 \\ ...=-8 \\ ...=28 \\ ...=-9 \end{cases}$ | $\begin{cases} ...=-0.25 \\ ...=-1 \\ ...=3 \\ ...=4.25 \end{cases}$ | QR |
| 7 | $\begin{cases} 3x_1+11x_2+x_3+6x_4=... \\ -x_1-3x_2+13x_3+16x_4=... \\ 2x_1+14x_2-4x_3+x_4=... \\ -x_1+7x_2+5x_3=... \end{cases}$ | $\begin{cases} ...=21 \\ ...=25 \\ ...=13 \\ ...=11 \end{cases}$ | $\begin{cases} ...=179 \\ ...=131 \\ ...=148 \\ ...=79 \end{cases}$ | $\begin{cases} ...=-11.5 \\ ...=-19 \\ ...=-7.25 \\ ...=-4 \end{cases}$ | LU |
| 8 | $\begin{cases} 2x_1+3x_2+x_3+x_4=... \\ 2x_1+x_3+3x_4=... \\ 7x_1-4x_2+x_3+x_4=... \\ x_1-12x_2+x_3+x_4=... \end{cases}$ | $\begin{cases} ...=7 \\ ...=6 \\ ...=5 \\ ...=-9 \end{cases}$ | $\begin{cases} ...=38 \\ ...=50 \\ ...=1 \\ ...=-53 \end{cases}$ | $\begin{cases} ...=-3.5 \\ ...=-4 \\ ...=-8.5 \\ ...=-1.25 \end{cases}$ | LU |
| 9 | $\begin{cases} 5x_1+3x_2-x_3+2x_4=... \\ 3x_1+6x_3-2x_3-2x_4=... \\ -x_1-2x_2+4x_3-x_4=... \\ 2x_1-2x_2-x_3-12x_4=... \end{cases}$ | $\begin{cases} ...=9 \\ ...=5 \\ ...=0 \\ ...=11 \end{cases}$ | $\begin{cases} ...=26 \\ ...=0 \\ ...=20 \\ ...=44 \end{cases}$ | $\begin{cases} ...=-4.75 \\ ...=-5 \\ ...=-3.75 \\ ...=-1.25 \end{cases}$ | QR |
| 10 | $\begin{cases} 6x_1+x_2+3x_3-2x_4=... \\ 6x_1+8x_2+x_3-x_4=... \\ 12x_1-2x_2+4x_3-x_4=... \\ 8x_1-+x_2+x_3+5x_4=... \end{cases}$ | $\begin{cases} ...=8 \\ ...=14 \\ ...=13 \\ ...=15 \end{cases}$ | $\begin{cases} ...=67 \\ ...=77 \\ ...=126 \\ ...=95 \end{cases}$ | $\begin{cases} ...=-5.25 \\ ...=0 \\ ...=-13.5 \\ ...=-7.25 \end{cases}$ | LU |

## 4 lentelė. Netiesinių lygčių sistemų sprendimas. Užduotys.
| Nr. | Lygčių sistema | Metodas
| --- | --- | --- |
| 1 | $\begin{cases} \frac{10x_1}{x^2_2+1}+x^2_1-x^2_2=0 \\ x^2_1+2x^2_2-32=0  \end{cases}$ | Niutono |
| 2 | $\begin{cases} cos(x_1)-x_1-x_2=0 \\ 20e^{-\frac{(x^2_1+x^2_2)}{4}}+\frac{x^2_1+x^2_2}{4}-10=0  \end{cases}$ | Broideno |
| 3 | $\begin{cases} x^2_1+(x_2+cos(x_1))^2-40=0 \\ (\frac{x_1}{2})^3+25x^2_2-50=0 \end{cases}$ | Niutono |
| 4 | $\begin{cases} \frac{x^3_2}{2}-\frac{x_2x^2_1}{5}-5=0 \\ (\frac{x_1}{4})^4+(\frac{x_2}{2})^2-4=0 \end{cases}$ | Broideno |
| 5 | $\begin{cases} \frac{x^2_1}{(x_2+cos(x_1))^2+1}-2=0 \\ (\frac{x_1}{3})^2+(x_2+cos(x_1))^2-5=0 \end{cases}$ | Niutono |
| 6 | $\begin{cases} x^2_2-x^2_1-5x_1cos(x_2+1)-10=0 \\ x^2_1+x^2_2+x_1x_2-20=0 \end{cases}$ | Broideno |
| 7 | $\begin{cases} x_1x_2-10=0 \\ (\frac{x_1}{x_4})^4+x^2_2 -x_1x_2-10=0 \end{cases}$ | Niutono |
| 8 | $\begin{cases} (x_1-3)^3+x_2-8=0 \\ \frac{x^2_1+x^2_2}{2}-6(cos(x_1)+cos(x_2))-10=0 \end{cases}$ | Broideno |
| 9 | $\begin{cases} x^2_1+10(sin(x_1)+cos(x_2))^2-10=0 \\ (x_2-3)^2+x_1-8=0 \end{cases}$ | Niutono |
| 10 | $\begin{cases} x^2_1+2(x_2-cos(x_1))^2-20=0 \\ x^2_1x^2-2=0 \end{cases}$ | Broideno |

**Pavyzdys**
| Lygčių sistema | Grafinis sprendinys | Pradinių artinių tinklelis |
| --- | --- | --- |
| $\begin{cases} -\frac{5x_2}{x^2_1+1}+x^2_2-x^2_1=0 \\ x^2_1+x^2_2-12=0 \end{cases}$ | <img src="grafinis_pavyzdys.png" alt="Grafinis pavyzdys" width="100"/> | <img src="pradiniu_artiniu_tinklelis.png" alt="Pradinių artinių tinklelis" width="100"/> |

## 5 lentelė. Optimizavimo uždaviniai.
| * rekomenduojama $n<=20$, $m<=20$ |
| --- |
| Uždavinys 1-3 variantams |
| Miestas išsidėstęs kvadrate, kurio koordinatės $(−10<=x<=10, −10<=y<=10)$. Mieste yra n $(n>=3)$ vieno tinklo parduotuvių, kurių koordinatės yra žinomos (Koordinatės gali būti generuojamos atsitiktinai, negali būti kelios parduotuvės toje pačioje vietoje). Planuojama pastatyti dar m $(m>=3)$ šio tinklo parduotuvių. Parduotuvės pastatymo kaina (vietos netinkamumas) vertinama pagal atstumus iki kitų parduotuvių ir miesto ribos. Reikia parinkti naujų parduotuvių vietas (koordinates) taip, kad parduotuvių pastatymo kainų suma būtų kuo mažesnė. Atstumo tarp dviejų parduotuvių, kurių koordinatės $(x_1, y_1)$ ir $(x_2, y_2)$, kaina apskaičiuojama pagal formulę: </br> $𝐶(x_1, y_1, x_2, y_2) = exp(−0.2 * ((x_1 − x_2)^2 + (y_1 − y_2)^2))$ </br> Atstumo tarp parduotuvės, kurios koordinatės $(x_1, y_1)$, ir artimiausio miesto ribos taško, kurio koordinatės $(x_r, y_r)$, kaina apskaičiuojama pagal formulę: </br> $C^R(x_1, y1, xr, yr) = \begin{cases} 0,\;jeigu\;parduotuvę\;planuojama\;statyti\;miesto\;ribose \\ exp(0.25 * ((x_1 − x_r)^2 + (y_1 − y_r)^2)) − 1, kitais\;atvejais \end{cases}$ |
| Uždavinys 4-6 variantams |
| Miestas išsidėstęs kvadrate, kurio koordinatės $(−10<=x<=10, −10<=y<=10)$. Mieste yra n $(n>=3)$ vieno tinklo parduotuvių, kurių koordinatės yra žinomos (Koordinatės gali būti generuojamos atsitiktinai, negali būti kelios parduotuvės toje pačioje vietoje). Planuojama pastatyti dar m $(m>=3)$ šio tinklo parduotuvių. Parduotuvės pastatymo kaina (vietos netinkamumas) vertinama pagal atstumus iki kitų parduotuvių ir miesto ribos. Reikia parinkti naujų parduotuvių vietas (koordinates) taip, kad parduotuvių pastatymo kainų suma būtų kuo mažesnė. Atstumo tarp dviejų parduotuvių, kurių koordinatės $(x_1, y_2)$ ir $(x_2, y_2)$, kaina apskaičiuojama pagal formulę: </br> $𝐶(x_1, y_1, x_2, y_2) = exp(−0.1 * ((x_1 − x_2)^2 + (y_1 − y_2)^2))$ </br> Atstumo tarp parduotuvės, kurios koordinatės $(x_1, y_1)$, ir artimiausio miesto ribos taško, kurio koordinatės $(x_r, y_r)$, kaina apskaičiuojama pagal formulę: </br> $C^R(x_1, y_1, x_𝑟, y_𝑟) = \begin{cases} 0,\;jeigu\;parduotuvę\;planuojama\;statyti\;miesto\;ribose \\ 0.5 * ((x_1 − x_r)^2 + (y_1 − y_r)^2),\;kitais\;atvejais \end{cases}$ |
| Uždavinys 7-8 variantams |
| Miestas išsidėstęs kvadrate, kurio koordinatės $(−10<=x<=10, −10<=x<=10)$. Mieste yra n $(n>=3)$ vieno tinklo parduotuvių, kurių koordinatės yra žinomos (Koordinatės gali būti generuojamos atsitiktinai, negali būti kelios parduotuvės toje pačioje vietoje). Planuojama pastatyti dar m $(m>3)$ šio tinklo parduotuvių. Parduotuvės pastatymo kaina (vietos netinkamumas) vertinama pagal atstumus iki kitų parduotuvių ir poziciją (koordinates). Reikia parinkti naujų parduotuvių vietas (koordinates) taip, kad parduotuvių pastatymo kainų suma būtų kuo mažesnė (naujos parduotuvės gali būti statomos ir už miesto ribos). </br> Atstumo tarp dviejų parduotuvių, kurių koordinatės $(x_1, y_1) ir (x_2, y_2)$, kaina apskaičiuojama pagal formulę: </br> $𝐶(x_1, y_1, x_2, y_2) = exp(−0.3 * ((x_1 − x_2)^2 + (y_1 − y_2)^2))$ </br> Parduotuvės, kurios koordinatės $(x_1, y_1)$, vietos kaina apskaičiuojama pagal formulę: </br> $C^P(x_1,y_1)=\frac{x^4_1+y^4_1}{1000}+\frac{sin(x_1)+cos(y_1)}{5}+0.4$ |