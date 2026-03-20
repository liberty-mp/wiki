---
title: Fisherman's Bounty 
---

| Întrebare | Răspuns |
| :-----------: | :-----------: |
| Event permanent? | Nu, [temporar.](./index.md#evenimentele-se-impart-in-3-categorii) |
| Nivel minim participare? | Nu. |
| Posibilitate găsire obiecte speciale? | [Da.](#treasure-map-rewards) |
| Necesită iteme specifice? | [Da.](#fisherman-s-bounty-🎣🗺%EF%B8%8F🗝%EF%B8%8F) |
| Locație statistici eveniment? | `Inventory` |

# Fisherman's Bounty 🎣🗺️🗝️  

Evenimentul cu care începem vara ne va oferi oportunitatea de a pleca în căutarea comorilor ascunse în zonele extraurbane ale hărții. Cât timp evenimentul este activ, jucătorii vor obține câte un Special Event Token pescuind, fiecare pește prins oferind un astfel de token. Event Tokens sunt tradable şi vor fi folosiți și la viitoare evenimente.

Lângă fiecare [pescar de pe hartă](../jobs/fisherman.md), acum este prezent asistentul Dembe, care îți va spune pe scurt ce să faci și îți va pune la dispoziție un magazin din care vei putea achiziționa Treasure Maps şi Shovel (lopată).

În momentul achiziției, jucătorii vor primi 4 X-uri (puncte) aleatorii, afișate pe Treasure Map, puncte pe care trebuie să le găsească și în care să sape în speranța găsirii unui cufăr de comori. Fiecare comoară dezgropată cu succes te va recompensa cu un Treasure Chest.

:::tip Informații:
Evenimentul **NU** are o limită de repetări pe zi. Poți rezolva câte Treasure Maps dorești.<br>
Poți avea maxim o hartă în inventar. Nu este tradable.<br>
Shovel-ul trebuie cumpărat doar o dată, nu se uzează.<br>
Event Tokens & Shovel & Fisherman's Bounty Crate **sunt tradable**.<br>
Event Tokens & Fisherman's Bounty Crate - maxim 65 bucăți/stack.<br>
Toate ticketele câștigate în cadrul evenimentului **sunt tradable**.<br>
:::

### Dembe's Shop

Vorbind cu Dembe, poți cumpăra următoarele obiecte folosind Special Event Tokens:

| Item | Tokens |
| :-: | :-: |
| <InventoryItem itemKey="fisherman_treasuremap" width="64" :qt="1" /> | <InventoryItem itemKey="special_event_token" width="64" :qt="80" /> |
| <InventoryItem itemKey="shovel" width="64" :qt="1" /> | <InventoryItem itemKey="special_event_token" width="64" :qt="25" /> |

### Treasure Map Rewards  

Un Treasure Map conține <InventoryItem itemKey="crate_fisherman_bounty" width="64" :qt="4" />

Acest crate conține unul dintre următoarele premii:
| Categoria Gri | Categoria Albastra | Categoria Mov | Categoria Rosie |
| :-: | :-: | :-: | :-: |
| <Dinero :amount="4000" /> - <Dinero :amount="7000" /> | <InventoryItem itemKey="c4_bomb" width="64" :qt="1" /> | <InventoryItem itemKey="vehicle_ds_standard_ticket_tradable" width="64" :qt="1" /> | <Gold :amount='750' /> - <Gold :amount='2000' /> |
| <InventoryItem itemKey="marked_money" width="64" :qt="8000" /> - <InventoryItem itemKey="marked_money" width="64" :qt="14000" /> | <InventoryItem itemKey="hooked_rope" width="64" :qt="1" /> | <InventoryItem itemKey="vehicle_plate_ticket_tradable " width="64" :qt="1" /> | Vehicle Slot |
| <InventoryItem itemKey="gunpowder" width="64" :qt="2" /> - <InventoryItem itemKey="gunpowder" width="64" :qt="4" /> | <InventoryItem itemKey="vintage_velvet_cigar" width="64" :qt="2" /> - <InventoryItem itemKey="vintage_velvet_cigar" width="64" :qt="5" /> | <InventoryItem itemKey="vehicle_headlights_ticket_tradable" width="64" :qt="1" /> | <InventoryItem itemKey="boombox" width="64" :qt="1" /> |
| <InventoryItem itemKey="metal" width="64" :qt="2" /> - <InventoryItem itemKey="metal" width="64" :qt="4" /> | <InventoryItem itemKey="regal_reserve_cigar" width="64" :qt="2" /> -  <InventoryItem itemKey="regal_reserve_cigar" width="64" :qt="4" /> | <InventoryItem itemKey="vehicle_custom_color_ticket_tradable " width="64" :qt="1" /> | <InventoryItem itemKey="vehicle_ds_ticket_tradable" width="64" :qt="1" /> |
| <InventoryItem itemKey="wires" width="64" :qt="2" /> - <InventoryItem itemKey="wires" width="64" :qt="5" /> | <InventoryItem itemKey="cocaine_powder" width="64" :qt="1" /> -  <InventoryItem itemKey="cocaine_powder " width="64" :qt="2" /> | <InventoryItem itemKey="vehicle_horn_ticket_tradable " width="64" :qt="1" /> | <InventoryItem itemKey="inventory_slots_ticket_tradable" width="64" :qt="1" /> |
| <InventoryItem itemKey="explosive" width="64" :qt="2" /> - <InventoryItem itemKey="explosive" width="64" :qt="4" /> | <InventoryItem itemKey="marijuana_blunt" width="64" :qt="1" /> - <InventoryItem itemKey="marijuana_blunt" width="64" :qt="2" /> | <InventoryItem itemKey="vehicle_neon_ticket_tradable" width="64" :qt="1" /> | <InventoryItem itemKey="gold_subscription_ticket_tradable" width="64" :qt="1" /> |
| <InventoryItem itemKey="drill" width="64" :qt="1" /> - <InventoryItem itemKey="drill" width="64" :qt="2" /> | <InventoryItem itemKey="tobacco_seeds" width="64" :qt="4" /> - <InventoryItem itemKey="tobacco_seeds" width="64" :qt="6" /> | <InventoryItem itemKey="name_change_ticket_tradable" width="64" :qt="1" /> | <InventoryItem itemKey="platinum_subscription_ticket_tradable" width="64" :qt="1" /> |
| <InventoryItem itemKey="pliers" width="64" :qt="1" /> - <InventoryItem itemKey="pliers" width="64" :qt="2" /> | <InventoryItem itemKey="vehicle_ds_economy_ticket" width="64" :qt="1" /> | <InventoryItem itemKey="vehicle_tyre_smoke_ticket_tradable" width="64" :qt="1" /> | <InventoryItem itemKey="vehicle_chameleon_ticket_tradable" width="64" :qt="1" /> |
| <InventoryItem itemKey="account_bonus_0" width="64" :qt="1" /> | - | <InventoryItem itemKey="vehicle_wheels_ticket_tradable" width="64" :qt="1" /> | - |
| <InventoryItem itemKey="account_bonus_1" width="64" :qt="1" /> | - | <InventoryItem itemKey="vehicle_trunk_ticket_tradable" width="64" :qt="1" /> | - |
| <InventoryItem itemKey="account_bonus_2" width="64" :qt="1" /> | - | <InventoryItem itemKey="vehicle_camber_ticket_tradable" width="64" :qt="1" /> | - |
| <InventoryItem itemKey="account_bonus_3" width="64" :qt="1" /> | - | <InventoryItem itemKey="vehicle_tcs_ticket_tradable" width="64" :qt="1" /> | - |
| - | - | <InventoryItem itemKey="vehicle_air_ride_ticket_tradable" width="64" :qt="1" /> | - |
| - | - | <InventoryItem itemKey="vehicle_engine_ticket_tradable" width="64" :qt="1" /> | - |

::: tip  INFO

<InventoryItem itemKey="account_bonus_0" width="64" /> are o durata de 6 ore sau 12 ore.

<InventoryItem itemKey="account_bonus_1" width="64" /> are o durata de 6 ore sau 12 ore.

<InventoryItem itemKey="account_bonus_2" width="64" /> are o durata de 6 ore sau 12 ore.

<InventoryItem itemKey="account_bonus_3" width="64" /> are o durata de 6 ore sau 12 ore.

Bomboxul il poti castiga doar daca **NU** il detii.
:::

În cazul în care ai nevoie de alte informații pe care nu le găsești pe această pagină, îți sugerăm să folosești sistemul de ajutor din joc (tastează `/helpme` sau `/n`), să accesezi serverul nostru de [**Discord**](https://liberty.mp/discord) sau să comunici cu alți jucători și să îi intrebi pe aceștia.
