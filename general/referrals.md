---
title: Referrals
---

## Programul de Referral

Programul de referral are ca obiectiv răsplătirea jucătorilor ce recomandă serverul la cunoștințe și aceștia introduc un ID unic sau numele persoanei ce a făcut recomandarea.

Fiecare jucător are un ID unic ce poate fi folosit ca și referral sau mai simplu, folosește numele propriu. ID-ul se poate afla în tab-ul "Referrals" din interfața de [Profil](./profile-and-settings.md#cum-vizualizez-profilul-și-setările). O explicație mai în detaliu al acestui tab - [Referrals](./profile-and-settings.md#referrals).

### Introducerea referral-ului

::: info Atenție!
Dacă te apuci împreună cu un prieten să vă jucați pe server, prietenul tău poate să introducă referral-ul tău și tu pe al lui cât timp nu depășești maximul de 3 ore jucate și alegi să nu-l introduci la finalizarea tutorialului (apeși Nu). Poți să introduci codul de referral după tutorial, în categoria "**Referrals**" din [Profil și setări](./profile-and-settings.md#cum-vizualizez-profilul-și-setările).
:::

::: warning Atenție
Poți introduce un referral după ce _termini tutorialul de început_ sau în **primele 10 ore jucate** pe server.
:::

::: details Introducere Referral:  
<Image src="https://i.imgur.com/60uMEl8.png" alt="Iref" />
:::

### Recompense 

**Persoana care recomandă serverul** are următoarele recompense atunci când cel care a introdus referral-ul (numele sau ID-ul unic) atinge numărul de ore menționat:

| Cerințe   | Recompense |
| :-----------: | :-----------: |
| 15 ore jucate | <Dinero :amount='2000' /> |
| 20 ore jucate | <InventoryItem itemKey="crate_trucker_event" width="64" :qt="1" />/|
| 30 ore jucate | <Dinero :amount='2500' /> |
| 40 ore jucate | <Gold :amount='250' /> |
| 75 ore jucate | [**clothing crate**](#clothing-crate) |
| 100 ore jucate | <InventoryItem itemKey="ammo_smg" width="64" :qt="100" />/ |
| 150 ore jucate | <Gold :amount='750' /> |

**Persoana ce a introdus referral-ul** (numele sau ID-ul unic) primește următoarele recompense atunci când atinge numărul de ore jucate:

| Cerințe   | Recompense |
| :-----------: | :-----------: |
| 5 ore jucate | <InventoryItem itemKey="marijuana_joint" width="64" :qt="10" />/ |
| 10 ore jucate | <Dinero :amount='2500' /> |
| 20 ore jucate | <Dinero :amount='3000' /> |
| 30 ore jucate | <InventoryItem itemKey="crate_trucker_event" width="64" :qt="2" />/ |
| 40 ore jucate | <Gold :amount='200' /> |
| 80 ore jucate | [**clothing crate**](#clothing-crate) |
| 100 ore jucate | <InventoryItem itemKey="weapon_pistol50" width="64" :qt="1" />/ |
| 125 ore jucate | <InventoryItem itemKey="ammo_smg" width="64" :qt="100" />/ |
| 150 ore jucate | <Gold :amount='700' /> |

**<Color hex="#FFD700">Gold</Color>**-ul este folosit în [Shop](https://ucp.liberty.mp/shop).

## Clothing Crate

În funcție de sexul caracterului, **Male** _sau_ **Female**, ales la crearea caracterului în joc, primiți aleatoriu o cutie ce conține haine:
::: details Posibile crate-uri  
| Crate (cutie)   | Ce conține? |
| :-----------: | :-----------: |
| <Image src="https://i.imgur.com/OFqUT7c.png" alt="CrateMT" width="100" label="Alpha Male Top Crate" />| haine din viața reală,<br> pt. bărbați<br>folosite în slot-ul Top |
| <Image src="https://i.imgur.com/MTLwxUA.png" alt="CrateML" width="100" label="Alpha Male Legs Crate" />| haine din viața reală,<br> pt. bărbați<br>folosite în slot-ul Legs |
| <Image src="https://i.imgur.com/iw7O1fV.png" alt="CrateMS" width="100" label="Alpha Male Shoes Crate" />| haine din viața reală,<br> pt. bărbați<br>folosite în slot-ul Shoes |
| <Image src="https://i.imgur.com/75jMgNa.png" alt="CrateFT" width="100" label="Alpha Female Top Crate" />| haine din viața reală,<br> pt. femei<br>folosite în slot-ul Top |
| <Image src="https://i.imgur.com/883DuGw.png" alt="CrateFL" width="100" label="Alpha Female Legs Crate" />| haine din viața reală,<br>pt. femei<br>folosite în slot-ul Legs |
| <Image src="https://i.imgur.com/jV12tMI.png" alt="CrateFS" width="100" label="Alpha Female Shoes Crate" />| haine din viața reală,<br>pt. femei<br>folosite în slot-ul Shoes |
| <Image src="https://i.imgur.com/1Xv2WIv.png" alt="CrateBM" width="100" label="Gamma Male Crate" />| haine din viața reală,<br>pt. bărbați<br>conține top, legs & shoes |
| <Image src="https://i.imgur.com/8k4oLpb.png" alt="CrateBF" width="100" label="Gamma Female Crate" />| haine din viața reală,<br>pt. femei<br>conține top, legs & shoes |

Mai multe informații despre [Slot-uri și inventar](./inventory.md#clothing-items).
:::

