---
title: Miner
---

| Întrebare   | Răspuns |
| ----------- | :-----------: |
| Câștig mediu pe ora? | ~<Dinero :amount='1500' /> |
| Necesită vehicul personal? | Nu, dar folosind unul îți va aduce mai mult profit, fiind mai performant. |
| Necesită permis de conducere? | Nu, dar ajută (categoria B). |
| Necesită iteme specifice? | Da, [târnăcop](#cum-fac-rost-de-tarnacop). |
| Posibilitate câștigare iteme extra? | [Da](#obiecte-speciale-pentru-crafting-si-alte-activitati-sanse-de-gasire). |
| Locație NPC Miner | <Image src="https://i.imgur.com/1ONfXp8.png" width="256" label="Grand Senora Desert, Joshua Rd" />  |

## Desfășurarea jobului  

Jobul de Miner constă în extragerea pietrelor din zonele de carieră folosind un târnăcop, apoi vânzarea acestora la NPC-ul Miner.

## Întrebări frecvente

### Cum fac rost de târnăcop?

Târnăcopul poate fi achiziționat de la orice business de tip **magazin 24/7** pentru prețul de **$100**.

::: details Târnăcop de lemn  
<Image src="https://i.imgur.com/xnKHxaq.png" alt="https://i.imgur.com/xnKHxaq.png" />
:::

Târnăcopul este un item consumabil, acesta având o durabilitate de **100 de pietre**. După ce ai spart 100 de pietre, târnăcopul se va distruge automat.

Pentru a vedea durabilitatea târnăcopului, apasă `CLICK DREAPTA` pe târnăcop-ul din inventar și selectează "**Inspect**".

::: details Durabilitate târnăcop
<Image src="https://i.imgur.com/GL8EWR0.png" alt="Durabilitate târnăcop" />
:::

### Cum fac rost de un târnăcop mai bun?

Există un târnăcop mai bun, de fier, care poate fi craftat la NPC-ul Miner.

Pentru a-l crafta, ai nevoie de următoarele iteme:

| Imagine | Cantitate necesară | Obținere |
| :---: | :---: | :---: |
| <Image src="https://i.imgur.com/i3Jt8cc.png" alt="Forged Grip" width="100" label="Forged Grip" /> | **30x** bucăți | Șansă de a obține din minat |
| <Image src="https://i.imgur.com/DBgM7yn.png" alt="Metal Blade" width="100" label="Metal Blade" /> | **30x** bucăți | Șansă de a obține din minat |

Acest târnăcop are o durabilitate aleatorie între **100 și 1000 de pietre**.  De asemenea capătă o șansă aleatorie între **5% și 30%** de a mina [Marble](#enciclopedie-pietre).

### Cum încep munca?

::: danger Atenție!
Pentru a putea începe job-ul de Miner, trebuie să deții un târnăcop în inventar. 

[Cum fac rost de târnăcop?](#cum-fac-rost-de-tarnacop)
:::

Odată ajuns la locația NPC-ului Miner, interacționează cu el folosind butonul `E` și selectează "**Începe munca**". Vei avea de ales dacă dorești să începi munca folosind vehiculul oferit de server sau unul personal. 

::: tip
Selectând vehiculul oferit de el, se va asigura că vei avea rezervorul de combustibil mereu plin, deci nu va trebui ca tu să acoperi costurile combustibilului.
:::

::: details Începe munca  
  <Image src="https://i.imgur.com/iTOr2Hv.gif" alt="Start Job" />
:::  

::: details Vehicul oferit de NPC  
  Caracara | Top speed: 155 km/h | Tracțiune: integrală | Viteze: 5 | Manevrabilitate: mare 
  <Image src="https://i.imgur.com/Hdi0Y0C.png" alt="Caracara" />
::: 

### Cum minez piatra?

Ca să minezi piatra, trebuie să ai târnăcopul echipat în unul din cele 5 fast slots din inventarul tău, numerotate cu numerele `1`, `2`, `3`, `4`, `5`. Pentru a echipa, apasă tasta `I` pentru a deschide inventarul și trage târnăcopul pe un fast slot.

::: details Echiparea târnăcopul  
  <Image src="https://i.imgur.com/trIAcc2.gif" alt="Echiparea târnăcopul" />
:::  

După ce ai început tura de muncă, trebuie să urmezi ruta de pe hartă până când ajungi la zona de minat a pietrelor. Pentru a mina piatra, coboară din mașină și apropie-te de punctul indicat de lângă rocă. Vei începe să minezi automat, iar când minatul este gata, piatra va fi automat adăugată în inventar. 

Când inventarul este plin, trebuie să mergi înapoi la NPC-ul Miner pentru a vinde pietrele.

::: details Minarea pietrei  
  <Image src="https://i.imgur.com/sVFI4zl.gif" alt="Minarea pietrei" />
::: 

::: details Vânzarea pietrelor  
  <Image src="https://i.imgur.com/XebMc3B.gif" alt="Vânzarea pietrelor" />
:::

### Enciclopedie pietre

Un tabel cu toate tipurile de pietre pe care le poți mina în zonele de carieră și prețurile lor de vânzare la NPC-ul Miner.

**ș.m.t = șansă minat târnăcop**

| **Imagine** | **Preț** per unitate | **ș.m.t din lemn** | **ș.m.t din fier** | **Considerată valoroasă?** |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| <Image src="https://i.imgur.com/cwMdibq.png" alt="Stone" width="64" label="Stone" /> | **<Dinero :amount='15' />** | **85%** | **65%** | Nu |
| <Image src="https://i.imgur.com/XyOLRvH.png" alt="Granite" width="64" label="Granite" /> | **<Dinero :amount='19' />** | **15%** | **35%** | Nu |
| <Image src="https://i.imgur.com/4UoM5HC.png" alt="Marble" width="64" label="Marble" /> | **<Dinero :amount='25' />** | **0%** | **5% - 30%** | Da |

## Obiecte speciale pentru crafting și alte activități & șanse de găsire  

Pe lângă suma de bani primită după descărcare, mai ai șansa de a găsi **obiecte speciale**, care te ajută la **alte activități** sau **în crafting**.  
::: tip Detalii șanse drop  
La fiecare $350 câștigați în cadrul job-ului există șansa de 25% de a găsi **Metal Bar**.

La fiecare $300 câștigați în cadrul job-ului există șansa de 25% de a găsi **Gunpowder**.

La fiecare $300 câștigați în cadrul job-ului există șansa de 25% de a găsi **Thermite**.

În sumele reprezentate mai sus, bonusurile ce afectează job-urile (ex: World Exploration, joint, Liberty Boost, clan perk) sunt incluse.

:::  
| **Imagine** | **Stackable?** | **Șansă de drop %** | **Utilitate**
| :-----------: | :-----------: | :-----------: | :-----------: |
| <Image src="https://i.imgur.com/wy3nrJG.png" alt="Metal Bar" width="48" label="Metal Bar" /> | **Da, 8 per stack** |  **25%, vezi deasupra tabelului**  | folosit in [Crafting](../general/crafting) |
| <Image src="https://i.imgur.com/Ub9vSWq.png" alt="Gunpowder" width="48" label="Gunpowder" /> | **Da, 32 per stack** |  **25%, vezi deasupra tabelului** | folosit in [Crafting](../general/crafting) |
| <Image src="https://i.imgur.com/2yZmE5w.png" alt="Thermite" width="48" label="Thermite" /> | **Da, 32 per stack** |  **25%, vezi deasupra tabelului** | folosit in [Crafting](../general/crafting) |

## Cazuri în care nu poți efectua jobul  
 
- Ai epuiat durabilitatea târnăcopului, acesta se va distruge automat și nu vei mai putea mina pietre.
::: details Târnăcop epuizat  
 <Image src="https://i.imgur.com/c67aVXW.png" alt="Târnăcop epuizat" />
:::

- Tura de job se oprește automat dacă abandonezi vehiculul pentru mai mult de _**5 minute**_. Nu sta AFK (away from keyboard) dacă nu ești la volanul vehiculului.  
::: details Abandon vehicul  
 <Image src="https://i.imgur.com/L6ut45T.png" alt="Abandon vehicul" />  
:::  

- Dacă mori, tura de job este anulată instant și pierdeți orice progres din vehiculul Caracara.  
::: details Moarte în timpul jobului  
 <Image src="https://i.imgur.com/9oNK7SN.png" alt="Moarte job Miner" />  
:::  
