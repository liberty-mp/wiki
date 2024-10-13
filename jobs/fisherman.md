---
title: Fisherman
---

| Întrebare   | Răspuns |
| ----------- | :-----------: |
| Câștig mediu pe ora? | ~<Dinero :amount='1700' /> |
| Cate ore jucate sunt necesare pentru a practica jobul?  | 10 ore jucate |
| Necesită vehicul personal? | Nu, dar folosind unul îți va aduce mai mult profit, fiind mai performant. |
| Necesită permis de conducere? | Nu, dar ajută (categoria A/B). |
| Necesită iteme specifice? | Da, undiță și momeală. |
| Posibilitate câștigare iteme extra? | [Da](#obiecte-speciale-pentru-crafting-si-alte-activitati-sanse-de-prindere). |
| Locație NPC-uri Fisherman | [Locație 1: Paleto Cove](https://i.imgur.com/yulA4MR.png) <br> [Locație 2: Galilee](https://i.imgur.com/X0R0TcL.png) <br> [Locație 3: Chumash Barbareno Road](https://i.imgur.com/G3jsp6P.png) | --->

## Desfășurarea jobului

Jobul de Fisherman constă în pescuitul peștilor folosind o undiță și momeală, apoi vânzarea acestora la unul dintre NPC-uri.  

## Locație pescuit  

Găsește un loc de pescuit, poți pescui doar în una dintre cele 3 locații Fisherman.  
O locație populară este pe plaja de lângă **Fisherman 3, Chumash** datorită locației unui **magazin 24/7** în apropiere. 

## Întrebări frecvente

### Cum fac rost de undiță?

Poți cumpăra o undiță normală, din lemn, dintr-un business de tip **magazin 24/7** pentru prețul de <Dinero :amount='100' />.  

::: details Undiță de lemn  
  <Image src="https://i.imgur.com/i8RG0sN.png" alt="Wooden Rod" />
:::

Undița normală are o durabilitate de 120, însemnând 120 pești prinși cu **succes**.  
Se spune că 4 din 10 pești reușesc să scape din cârlig când folosești această undiță (40% șansă ca peștele să scape înainte de a fi prins).
Pentru a vedea durabilitatea undiței, apasă _**click dreapta**_ pe undiță în inventar, apoi selectează "**Inspect**".

::: details Durabilitate undiță
  <Image src="https://i.imgur.com/l24Y6He.png" alt="Rod Durability" />
:::  
 
### Cum fac rost de o undiță mai bună?  

Poți crafta o undiță specială, din fibră de carbon, la NPC-ul Fisherman localizat la fiecare locație pe hartă cu iconița <Image src="https://i.imgur.com/W89GtyV.png" alt="Fisherman" />

Pentru a o crafta, ai nevoie de următoarele obiecte:
| Imagine | Cantitate necesară | Obținere |
| :---: | :---: | :---: |
| <Image src="https://i.imgur.com/Wnnlxz8.png" alt="Rod Guide" width="100" label="Rod Guide" /> | **30x** bucăți | Șansă de a obține din pescuit |
| <Image src="https://i.imgur.com/IF3BKBI.png" alt="Rod Grip" width="100" label="Rod Grip" /> | **25x** bucăți | Șansă de a obține din pescuit |
| <Image src="https://i.imgur.com/mF8EOhE.png" alt="Reel Rod" width="100" label="Reel Rod" /> | **1x** bucată | Șansă de a obține din pescuit |  

Această undiță capătă o durabilitate aleatorie între _**100**_ și _**1000**_. De asemenea capătă o șansă aleatorie între _**5%**_ și _**30%**_ de a prinde un pește mai valoros.  
Se spune că doar 1 din 10 pești reușește să scape din cârlig când folosești această undiță (10% sansă ca peștele să scape înainte de a fi prins).  

### Cum fac rost de momeală?

O poți cumpăra dintr-un business de tip **magazin 24/7** pentru prețul de <Dinero :amount='64' /> pentru **64** bucăți de momeală.  

::: details Momeală în magazin   
  <Image src="https://i.imgur.com/qdsVOWE.png" alt="Shop Fishrod" width="125" />
:::  

O bucată de momeală este folosită de fiecare dată când încerci să pescuiești.

### Cum pescuiesc?

Ca să pescuiești trebuie să echipezi undița în unul din cele 5 fast slot-uri din inventarul tău, numerotate cu numerele `1`, `2`, `3`, `4`, `5`. Pentru a echipa, apasă tasta `I` pentru a deschide inventarul și trage undița pe un fast slot.

::: details Echiparea undiței  
  <Image src="https://i.imgur.com/XpaQb63.gif" />
:::  

După ce am echipat undița într-un fast slot din inventar, apăsăm tasta respectivă (1-5) pentru a pune undița în mâini, apăsăm tasta `SPACE` în checkpoint-ul mov apărut pe hartă. Culoarea roșie indică faptul că așteptăm până când un pește va mușca momeala.  

::: details Exemplu pescuit  
  <Image src="https://i.imgur.com/lOzA7b6.gif" alt="Exemplu fish" />
  <Image src="https://i.imgur.com/iEIXiwt.png" alt="Exemplu minigame" />
:::  

Vom apăsa din nou tasta `SPACE` atunci când indicatorul devine culoarea verde, însemnând că peștele a mușcat momeala. Pe această săgeata vor aparea cifrele 3, 2, 1, 0, care indică câte secunde mai avem până când peștele va scăpa din cârlig (ducând la **pierderea peștelui**). Dacă am reușit să apăsăm la momentul potrivit, va apărea un mini-game în partea din mijloc-jos a ecranului, unde trebuie ca jucatorul să apese tasta `SPACE` când indicatorul sub formă de pește se află în pătratul verde.
În funcție de undița folosită, există șanse ca peștele să scape din cârlig chiar dacă jucătorul a apăsat când trebuie.
Pentru a putea vedea dacă peștele a fost prins sau nu, vei putea verifica notificarea plasată deasupra hărții, care va indica și ce fel de peste ai prins, dacă ai prins un obiect special sau dacă nu îndeplinești o cerință pentru a pescui.
Fiecare pește prins ocupă un slot din inventarul jucătorului, alături de prețul acestuia dacă ținem cursorul mouse-ului pe el.

::: warning
După un anumit număr de pești prinși, serverul iți va cere să schimbi zona de pescuit, urmărind punctul mov de pe hartă.
:::

### Unde se vinde peștele?

Peștii prinși se pot vinde la oricare dintre cei 3 NPC Fisherman aflați pe insulă la iconița <Image src="https://i.imgur.com/W89GtyV.png" alt="Fisherman Icon" width="32" />.

::: details Locație 1: Paleto Cove
  <Image src="https://i.imgur.com/yulA4MR.png" alt="Paleto Cove, Fisherman 1" />
:::  

::: details Locație 2: Galilee
  <Image src="https://i.imgur.com/X0R0TcL.png" alt="Galilee, Fisherman 2" />
:::  

::: details Locație 3: Chumash 
  <Image src="https://i.imgur.com/G3jsp6P.png" alt="Chumash, Fisherman 3" />
:::  

## Enciclopedie pești
Un tabel cu toți peștii din apele statului San Andreas și șansele de prindere:  

**ș.p.u = șansă prindere undiță**
| **Imagine** | **Preț** | **ș.p.u. din lemn** | **ș.p.u. din fibră de carbon** | **Considerat valoros?** |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| <Image src="https://i.imgur.com/vCLbj0r.png" alt="Bitterling" width="64" label="Bitterling" /> | **<Dinero :amount='15' />** | **24%** | **0%** | Nu |
| <Image src="https://i.imgur.com/ayekP7W.png" alt="Bluefin Tuna" width="64" label="Bluefin Tuna" /> | **<Dinero :amount='19' />** | **0%** | **33%** | Da |
| <Image src="https://i.imgur.com/w6zNIt3.png" alt="Common Carp" width="64" label="Common Carp" /> | **<Dinero :amount='13' />** | **0%** | **20%** | Nu |
| <Image src="https://i.imgur.com/ZzudxmG.png" alt="Common Dentex" width="64" label="Common Dentex" /> | **<Dinero :amount='13' />** | **0%** | **20%** | Nu |
| <Image src="https://i.imgur.com/Xd7pBSZ.png" alt="Common Pandora" width="64" label="Common Pandora" /> | **<Dinero :amount='15' />** | **0%** | **8%** | Nu |
| <Image src="https://i.imgur.com/aIlcJy7.png" alt="European Hake" width="64" label="European Hake" /> | **<Dinero :amount='16' />** | **0%** | **8%** | Nu |
| <Image src="https://i.imgur.com/sDWEmf6.png" alt="Gold Fish" width="64" label="Gold Fish" /> | **<Dinero :amount='23' />** | **0%** | **17%** | Da |
| <Image src="https://i.imgur.com/EWQCtdW.png" alt="Guvid" width="64" label="Guvid" /> | **<Dinero :amount='17' />** | **12%** | **0%** | Nu |
| <Image src="https://i.imgur.com/gKQykl2.png" alt="Hamsie" width="64" label="Hamsie" /> | **<Dinero :amount='17' />** | **12%** | **0%** | Nu |
| <Image src="https://i.imgur.com/lJPOxZT.png" alt="Lobster" width="64" label="Lobster" /> | **<Dinero :amount='22' />** | **0%** | **32%** | Da |
| <Image src="https://i.imgur.com/9YSh8Tq.png" alt="Monkfish" width="64" label="Monkfish" /> | **<Dinero :amount='16' />** | **0%** | **12%** | Nu |
| <Image src="https://i.imgur.com/uIL6Hil.png" alt="Mosquito" width="64" label="Mosquito" /> | **<Dinero :amount='16' />** | **26%** | **0%** | Nu |
| <Image src="https://i.imgur.com/JEHTuKk.png" alt="Prussian Carp" width="64" label="Prussian Carp" /> | **<Dinero :amount='13' />** | **0%** | **20%** | Nu |
| <Image src="https://i.imgur.com/2Qkoa9W.png" alt="Rainbow Fish" width="64" label="Rainbow Fish" /> | **<Dinero :amount='15' />** | **26%** | **0%** | Nu |
| <Image src="https://i.imgur.com/Ki860Lq.png" alt="Sparus" width="64" label="Sparus" /> | **<Dinero :amount='16' />** | **0%** | **0%** | Nu |
| <Image src="https://i.imgur.com/BQVLCfo.png" alt="Yabby" width="64" label="Yabby" /> | **<Dinero :amount='24' />** | **0%** | **17%** | Da |

## Obiecte speciale pentru crafting și alte activități & șanse de prindere  

Pe lângă peștele prins, mai ai o șansă la a prinde **obiecte speciale** care te ajută **în crafting** sau la **alte activități**.  

::: tip Detalii șanse drop

La fiecare $300 câștigați în cadrul job-ului există șansa de **25%** de a găsi Cloth.

În suma reprezentă mai sus, bonusurile ce afectează job-urile (ex: World Exploration, joint, Liberty Boost, clan perk) sunt incluse.

:::

| Imagine | Șansă de drop % | Utilitate
| :-----------: | :-----------: | :-----------: |
| <Image src="https://i.imgur.com/Wnnlxz8.png" alt="Rod Guide" width="100" label="Rod Guide" /> | **49%**  | Craftarea unei undițe speciale |
| <Image src="https://i.imgur.com/IF3BKBI.png" alt="Rod Grip" width="100" label="Rod Grip" /> |  **49%** | Craftarea unei undițe speciale |
| <Image src="https://i.imgur.com/mF8EOhE.png" alt="Reel Rod" width="100" label="Reel Rod" /> | **2%**  | Craftarea unei undițe speciale |
| <Image src="https://i.imgur.com/bRzgIRp.png" alt="Cloth" width="100" label="Cloth" /> | **25%** | [Spray Tags](/clans/spray-wars/spray-tags) |

## Cazuri în care nu poți efectua jobul   
 
- Dacă nu sunteti aflați în checkpoint-ul mov care vă apare după ce echipați undița, veți fi înștiințati printr-o notificare deasupra hărții.  
::: details Nu poți să pescuiești aici  
 <Image src="https://i.imgur.com/Lo3lPzj.png" alt="Eroare loc" />  
:::  

- Dacă nu ai spațiu în inventar pentru peștele prins, nu poți să pescuiești.  
::: details Nu ai loc in inventar  
 <Image src="https://i.imgur.com/rE8Cvc9.png" alt="Eroare spatiu inventar" />  
:::  

- Dacă nu ai momeală în inventar, nu poți să pescuiești.  
::: details Nu ai momeală in inventar  
 <Image src="https://i.imgur.com/1zQ91yu.png" alt="Eroare momeala" />  
:::  

