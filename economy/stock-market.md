---
title: Stock market
---

### Informatii despre stock market

Stock marketul reprezinta sistemul prin care jucatorii pot deveni beneficiari reali ai afacerilor de pe server. Sistemul implementat doreste sa mimeze conceptul real al actiunilor, cu anumite detalii adaptate jocului.

::: tip
Comercializarea de actiuni se face prin intermediul aplicatiei **Bank** din telefon, din ultima categorie din meniu si este disponibila doar in intervalul orar **08:00 - 23:00**.
:::

<Image src="https://i.imgur.com/68lduyt.png" alt="stocks"/>

## Vanzarea si cumpararea de actiuni

Vanzarea si cumpararea actiunilor functioneaza pe baza de orders, pe scurt, oferte de vanzare sau cumparare plasate de jucatori pe piata.

| Sell orders | Buy orders |
| :-----------: | :-----------: |
| <Image src="https://i.imgur.com/CMq0CEZ.png" alt="sell orders"/> | <Image src="https://i.imgur.com/whBxl3I.png" alt="buy orders"/>

Luand ca exemplu situatiile prezentante in screenshoturi, putem vedea ordinele de vanzare sau cumparare ordonate crescator (in cazul ordinelor de vanzare) sau descrescator (in cazul ordinelor de cumparare), cea mai benefica oferta disponibila fiind reprezentata intotdeauna prima.

Presupunem ca jucatorul doreste sa achizitioneze 5 actiuni din aceasta afacere la cel mai mic pret disponibil, acesta va pune un ordin de cumparare cu pretul de $20.000 per actiune in felul urmator:

<Image src="https://i.imgur.com/f8Um39X.png" alt="placing a buy order"/>

In momentul plasarii ordinului, sistemul va asocia cele doua ordine iar tranzactia va fi incheiata, vanzatorul primindu-si banii, iar cumparatorul actiunile. Ambii participanti vor fi informati printr-un email pe telefonul din joc despre solutionarea ordinelor.

#### Particularitati ale ordinelor de cumparare

Ordinele de cumparare **nu** trebuie sa fie in mod obligatoriu exacte din punct de vedere al pretului pentru ca tranzactia sa ia loc, spre exemplu daca o sa plasam un ordin de cumparare de 1 share pentru suma de $21.000, sistemul il va asocia tot cu ordinul de vanzare de $20.000, pretul de pe piata fiind mai avantajos decat pretul cerut in ordin, iar restul de $1.000 este restituit catre cumparator.

<Image src="https://i.imgur.com/tCNN9Qq.png" alt="purchase email"/>

Un exemplu si mai interesant este in momentul in care dorim sa cumparam 50 actiuni cu un pret maxim de $25.000, tranzactia solutionandu-se cu achizitia celor 17 actiuni ramase la pretul de $20.000, iar restul la $25.000 disponibile pe piata.

Ordinul plasat de noi (50 actiuni * $25.000) insumeaza $1.250.000.

**Cum a fost de fapt incheiata tranzactia:**
| Nr. actiuni | Pret per actiune | Total |
| :-----------: | :-----------: | :-----------: |
| 17 | $20.000 | $340.000 |
| 33 | $25.000 | $825.000 |

Cost total = $1.165.000

Drept urmare, $85.000 ne revin inapoi in cont datorita faptului ca a fost gasita o oferta mai benefica (cele 17 actiuni la pretul de $20.000).

<Image src="https://i.imgur.com/mcOpQMi.png" alt="purchase email"/>

## Distribuirea profitului din afaceri

::: tip
Toate afacerile prezente pe server produc bani in urma serviciilor oferite jucatorilor.

**ex:** 24/7 Market ofera spre vanzare diferite articole pe care jucatorii le cumpara, banii din vanzari ajung in balanta afacerii.
:::

::: info
Jucatorii pot verifica veniturile unui business in aplicatia de stock market la graficul "Revenue evolution"

<Image src="https://i.imgur.com/GeoNjsb.png" alt="revenue evolution"/>
:::
Distribuirea de venituri catre actionari (sau in termeni economici, dividende) se va realiza in momentul in care businessul a strans suficienti bani incat sa poata plati **minim $1 per actiune** detinuta de catre jucatori.

Distribuirea, in cazul in care conditiile sunt indeplinite, se va efectua in decursul fiecare nopti in jurul orei 3 AM.

Luand ca exemplu o situatie in care afacerea a strans suficienti bani incat sa poata plati fiecare actionar cu $10 per actiune, iar jucatorul detine un numar de 20 de actiuni, acesta o sa fie platit cu $200. Jucatorul o sa fie informat pe email de fiecare data.

<Image src="https://i.imgur.com/CGI69MW.png" alt="dividends"/>


