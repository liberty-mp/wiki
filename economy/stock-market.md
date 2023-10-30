---
title: Stock market
---

### Informații despre stock market

Stock marketul reprezintă sistemul prin care jucătorii pot deveni beneficiari reali ai afacerilor de pe server. Sistemul implementat dorește să mimeze conceptul real al acțiunilor, cu anumite detalii adaptate jocului.

::: tip
Comercializarea de acțiuni se face prin intermediul aplicației **Bank** din telefon, din ultima categorie din meniu și este disponibilă doar în intervalul orar **08:00 - 00:00**.<br>
**Vânzarea și cumpărarea de stock-uri este deblocată începând cu nivel 7.**
:::

<Image src="https://i.imgur.com/68lduyt.png" alt="stocks"/>

## Vânzarea și cumpărarea de acțiuni

Vânzarea și cumpărarea acțiunilor funcționează pe bază de orders, pe scurt, oferte de vânzare sau cumpărare plasate de jucători pe piață.

| Sell orders | Buy orders |
| :-----------: | :-----------: |
| <Image src="https://i.imgur.com/CMq0CEZ.png" alt="sell orders"/> | <Image src="https://i.imgur.com/whBxl3I.png" alt="buy orders"/>

Luând ca exemplu situațiile prezentate în screenshot-uri, putem vedea că ordinele de vânzare sau cumpărare sunt ordonate crescător (în cazul ordinelor de vânzare) sau descrescător (în cazul ordinelor de cumpărare), cea mai benefică ofertă disponibilă fiind reprezentată întotdeauna prima.

Presupunem că jucătorul dorește să achiziționeze 5 acțiuni din această afacere la cel mai mic preț disponibil, acesta va pune un ordin de cumpărare cu prețul de $20.000 per acțiune in felul următor:

<Image src="https://i.imgur.com/f8Um39X.png" alt="placing a buy order"/>

În momentul plasării ordinului, sistemul va asocia cele două ordine iar tranzacția va fi încheiată, vânzătorul primindu-și banii, iar cumpărătorul acțiunile. Ambii participanți vor fi informați printr-un email pe telefonul din joc despre soluționarea ordinelor.

#### Particularități ale ordinelor de cumpărare

Ordinele de cumpărare **nu** trebuie să fie în mod obligatoriu exacte din punct de vedere al prețului pentru ca tranzacția să ia loc, spre exemplu dacă o să plasăm un ordin de cumpărare de 1 share pentru suma de $21.000, sistemul îl va asocia tot cu ordinul de vânzare de $20.000, prețul de pe piață fiind mai avantajos decât prețul cerut în ordin, iar restul de $1.000 este restituit către cumpărător.

<Image src="https://i.imgur.com/tCNN9Qq.png" alt="purchase email"/>

Un exemplu și mai interesant este în momentul în care dorim să cumpărăm 50 acțiuni cu un preț maxim de $25.000, tranzacția soluționându-se cu achiziția celor 17 acțiuni rămase la prețul de $20.000, iar restul la $25.000 disponibile pe piață.

Ordinul plasat de noi (50 acțiuni * $25.000) însumează $1.250.000.

**Cum a fost de fapt încheiată tranzacția:**
| Nr. acțiuni | Preț per acțiune | Total |
| :-----------: | :-----------: | :-----------: |
| 17 | $20.000 | $340.000 |
| 33 | $25.000 | $825.000 |

Cost total = $1.165.000.

Drept urmare, $85.000 ne revin înapoi în cont datorită faptului că a fost găsită o ofertă mai benefică (cele 17 acțiuni la prețul de $20.000).

<Image src="https://i.imgur.com/mcOpQMi.png" alt="purchase email"/>

Ordinele de vânzare/cumpărare se vor completa și jucătorul va primi banii doar după ce toate acțiunile puse la vânzare se vor cumpăra, până atunci va fi prezentă o bară de progres arătând câte acțiuni au fost vândute/cumpărate, spre exemplu: 

<Image src="https://i.imgur.com/IEckDeh.png" alt="shares on hold"/>

<Image src="https://i.imgur.com/2OKQYml.png" alt="shares on hold"/>

Dacă jucătorul decide că nu mai dorește să vândă în continuare acțiunile, poate anula ordinul de vânzare primind înapoi acțiunile nevândute respectiv banii pe cele vândute, la ordinul de cumpărare, după anularea acestuia jucătorul rămâne cu acțiunile cumpărate și restul de bani i se vor transfera înapoi în cont.


## Distribuirea profitului din afaceri

::: tip
Toate afacerile prezente pe server produc bani în urma serviciilor oferite jucătorilor.

**ex:** 24/7 Market oferă spre vânzare diferite articole pe care jucătorii le cumpără, banii din vânzări ajung în balanța afacerii.
:::

::: info
Jucătorii pot verifica veniturile unui business în aplicația de stock market la graficul "Revenue evolution".

<Image src="https://i.imgur.com/GeoNjsb.png" alt="revenue evolution"/>
:::
Distribuirea de venituri către acționari (sau în termeni economici, dividende) se va realiza în momentul în care businessul a strâns suficienți bani încât să poată plăti **minim $1 per acțiune** deținută de către jucători.

Distribuirea, în cazul în care condițiile sunt îndeplinite, se va efectua în decursul fiecărei nopți în jurul orei 3 AM.

Luând ca exemplu o situație în care afacerea a strâns suficienți bani încât să poată plăti fiecare acționar cu $10 per acțiune, iar jucătorul deține un număr de 20 de acțiuni, acesta o să fie plătit cu $200. Jucătorul o sa fie informat pe email de fiecare dată.

<Image src="https://i.imgur.com/CGI69MW.png" alt="dividends"/>


