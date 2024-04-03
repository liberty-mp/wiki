---
title: Clan Tabs
---

## Members

Tab-ul 'MEMBERS' prezintă informații generale despre membrii clanului.

### Name

Numele jucătorului.


### Rank

Rank-ul jucătorului.

### Joined

Timp trecut de la intrarea în clan. 


### Deposited

Totalul de $ Money/Gold depozitat în seiful clanului.

### Manage

Secțiune văzută de liderul clanului.

::: details Detalii Member Management
Member Management Menu
<Image src="https://i.imgur.com/bVpwmZi.png" alt="Member Management Menu" />
Manage Member Permissions
<Image src="https://i.imgur.com/CGxGkR3.png" alt="Manage Member Permissions" />
Change Member Rank
<Image src="https://i.imgur.com/iKexOGX.png" alt="Change Member Rank" />
Transfer Clan Ownership
<Image src="https://i.imgur.com/ClJyXUC.png" alt="Transfer Clan Ownership" />
:::

## Vehicles

Vehiculele clanului, cumpărate din Dealership-ul respectiv folosind $ Money/Gold (Gold-ul este folosit în loc de tickete) din seiful clanului!

::: warning ATENŢIE!
Tunning-ul nu este încă implementat pentru vehiculele clanului!
:::

::: details Clan Vehicles (click)
<Image src="https://i.imgur.com/6S3uoUd.png" alt="Clan Vehicle Buy" />\
<Image src="https://i.imgur.com/LMBI9bZ.png" alt="Clan Vehicle Overview" />
<Image src="https://i.imgur.com/4OG1oLC.png" alt="Clan Vehicles Enter" />
:::

Dacă conducerea clanului decide să achiziționeze vehicule pentru clan, acestea pot fi utilizate de membrii clanului, cu condiția să aibă un rang minim stabilit de lider. Jucătorii care nu fac parte din clan nu au dreptul să le utilizeze.

## Perks

Perk-urile clanului sunt beneficii ce sunt cumpărate folosind $ Money și Gold din seiful clanului.

**Ca membru al clanului poți depozita $ Money și Gold în seiful clanului iar liderul poate dona la un anumit perk pentru a crește nivelul perk-ului.**

::: details Perks Overview
<Image src="https://i.imgur.com/Nms0CFV.png" alt="Perks Overview" />
:::

| Perk | Perk Description |
| :--: | :--: |
| <Image src="https://i.imgur.com/KZfM3aZ.png" alt="TEAMWORK EMPOWERMENT" width="180" /> | Maximize performance and provide better compensation for clan members. |
| <Image src="https://i.imgur.com/k2gh56h.png" alt="ADVANCED CONNECTIONS" width="180" /> | Police relations enhancement. Decreases wanted duration for clan members. |
| <Image src="https://i.imgur.com/MLFauAy.png" alt="HEIST MASTERY" width="180" /> | Enhance coordination among clan members for higher earnings in heists/robberies. |
| <Image src="https://i.imgur.com/EF9OX8H.png" alt="ADVANCED SKILL DEVELOPMENT" width="180" /> | Enhance concentration during heists and earn incresead # Street Reputation Points. |
| <Image src="https://i.imgur.com/r5kRln3.png" alt="BATTLEFIELD INTEGRATION" width="180" /> | Gain access to the clan warfare system, allowing your clan to comple for control over districts. |
| <Image src="https://i.imgur.com/G6RRoJU.png" alt="TAGGING EFFICIENCY" width="180" /> | Gain the advantage and reduce the time required overwrite enemy tags and create your own. |
| <Image src="https://i.imgur.com/G8TkdpG.png" alt="MONEY LAUNDERING" width="180" /> | Lowers the server tax applied during the 'Money Laundering' opperation. | 
| <Image src="https://i.imgur.com/NLZchPn.png" alt="MASTER OF PASSIVE GAINS" width="180" /> | Increases the amount of money received at the end of a passive shift. | 


## Perk Level-UP Table

Tabelul de mai jos se aplică la toate perk-urile, excepţie fiind la perk-urile Money Laundering, Battlefield Integration si Tagging Effeciency. Informaţiile se vor regăsi mai jos.
Boost-urile nu se acumulează, boost-ul maxim pentru orice perk fiind 25%/membru.

| Perk Level | $ Money Required | Gold Required | Time to Upgrade | % Boost |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | 
| 0 | BASIC | BASIC | BASIC | 0% |
| 1 | <Dinero :amount='100000'/> | <Gold :amount='500'/> | 1h30m | 5% |
| 2 | <Dinero :amount='250000'/> | <Gold :amount='1000'/> | 2h30m | 10% |
| 3 | <Dinero :amount='450000'/> | <Gold :amount='2500'/> | 4 hours | 15% |
| 4 | <Dinero :amount='1000000'/> | <Gold :amount='3500'/> | 6 hours | 20% |
| 5 | <Dinero :amount='2500000'/> | <Gold :amount='5000'/> | 12 hours| 25% |

În cazul job boost-ului, procentul este din câștigul de bază a jobului (se poate aduna cu marijuana joint, world exploration) dar nu și cu procentul de la skill-ul jobului.

Money Laundering Level-UP Table

| Perk Level | $ Money Required | Gold Required | Time to Upgrade | % of Marked Money |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | 
| 1 | <Dinero :amount='250000'/> | <Gold :amount='1000'/> | 1h30m | 35% |
| 2 | <Dinero :amount='450000'/> | <Gold :amount='2000'/> | 1h30m | 40% |
| 3 | <Dinero :amount='1000000'/> | <Gold :amount='3000'/> | 1h30m | 45% |
| 4 | <Dinero :amount='2000000'/> | <Gold :amount='7000'/> | 1h30m | 50% |
| 5 | <Dinero :amount='5000000'/> | <Gold :amount='15000'/> | 1h30m | 55% |

`% of Marked Money` reprezintă suma de bani pe care player-ul o va primi în urma procesului de Laundering. De exemplu, dacă player-ul face parte dintr-un clan ce are level 1 la perk-ul Money Laundering, din <MarkedMoney :amount="10000" /> 35%, adică <Dinero :amount='3500'/>.

Battlefield Integration Table

| Perk Level | $ Money Required | Gold Required | Time to Upgrade |
| :-----------: | :-----------: | :-----------: | :-----------: | 
| 1 | <Dinero :amount='10000000'/> | <Gold :amount='25000'/> | Instant |

Tagging Effeciency Level-UP Table

::: Timpul de așteptare pentru ștergerea / crearea unui tag este de **5 minute** fară upgrade la perk-ul Tagging Effeciency. 
:::

| Perk Level | $ Money Required | Gold Required | Time to Upgrade | Effeciency % of time | Time Left |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | 
| 1 | <Dinero :amount='2500000'/> | <Gold :amount='2000'/> | Instant | 5% | 4 min și 45 sec |
| 2 | <Dinero :amount='5000000'/> | <Gold :amount='5000'/> | Instant | 10% | 4 min și 30 sec |
| 3 | <Dinero :amount='8500000'/> | <Gold :amount='10000'/> | Instant | 15% | 4 min și 15 sec | 
| 4 | <Dinero :amount='13500000'/> | <Gold :amount='20000'/> | Instant | 25% | 3 min și 45 sec |
| 5 | <Dinero :amount='16500000'/> | <Gold :amount='30000'/> | Instant | 33% | 3 min și 21 sec |

`Effeciency % of time` reprezintă timpul redus pentru ștergerea tag-ului inamic sau crearea tag-ului propriu. De exemplu, dacă un jucător face parte dintr-un clan ce are level 3 la perk-ul Tagging Effeciency, acesta trebuie să aștepte 15% din 5 minute, adică 4 minute și 15 secunde.
