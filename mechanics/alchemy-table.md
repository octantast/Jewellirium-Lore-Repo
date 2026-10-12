# Alchemy table

> Source note: the descriptions follow the Android APK build, the most current version. The PC build is slightly older. Exact numbers are not given. The table of pieces below comes from the PC scripts and lists only the composition.

The alchemy table is where the player combines materials into a formula. A found formula opens a jewelry piece that customers can then order. The game has 61 jewelry pieces.

**The Perfect Man (author):** the crafting screen of the alchemy table is the process of assembling the Perfect Man. The schemes fill in with the progress of crafting: every found formula adds a piece to the counter "x/61", and the complete set is the Perfect Man. The unlocked pieces are kept after a reset of the cycle.

Related files: [README](../README.md), [bargaining](bargaining.md), [operations](operations.md), [basement](basement.md), [showcase](../showcase/showcase.md), [patron upgrades](../upgrades/patron-upgrades.md), [glossary](../glossary.md)

## Materials

The game has three kinds of material, all synthesized in the basement ([basement](basement.md)):

- **Metals** (screen label METALS).
- **Semi-precious stones** (screen label SEMI-PRECIOUS STONES; script name `stones`).
- **Precious stones** (screen label PRECIOUS STONES; script name `brilliants`).

## Slots and formulas

- The table starts with 3 slots (author's confirmation). The closed slots are shown covered with red wax seals and open through the patron's upgrades. The upgrades "alchemical table light", "alchemical table extension" and "NEW alchemical TOOLs" add one slot each, which gives up to 6 slots ([patron upgrades](../upgrades/patron-upgrades.md)).
- Placing a unit into a slot takes it from the stock (confirmed on a screenshot: the count of semi-precious stones fell by one when a stack of stones was placed; [screens](../interface/screens.md)). Closing the table without crafting returns the placed units to the stock.
- **Slot order (author's confirmation):** the slots are numbered clockwise starting from the bottom-right slot: 1 bottom right, 2 bottom centre, 3 bottom left, 4 top left, 5 top, 6 top right. Slots 4, 5 and 6 are the ones covered with seals at the start and open one by one through the patron's upgrades ([patron upgrades](../upgrades/patron-upgrades.md)). The examination hint on the screenshot shows slot 1 (the bottom-right slot), so the new formula begins with a metal. The crafts on the screenshots agree with the order: one stone in slot 1, and a metal in slot 1 with a semi-precious stone in slot 2.
- **Craft by the examination hint (author's craft):** the hint showed a metal in slot 1. The author crafted a piece from one metal and the game found a new formula. By its materials the piece is index 2 (`koronka`), the only piece made from one metal. The author describes the picture as a holder for an eyebrow; the script name does not describe it. The drawers show metals 7 after the craft, one below the earlier 8 ([screens](../interface/screens.md)).
- **Craft of a three-unit piece (author's craft):** one metal in slot 1, one semi-precious stone in slot 2 and one precious stone in slot 3 gave a new formula, the counter of found formulas grew. By its materials the piece is index 11 (`naperstok`), the only piece with one unit of each kind. The empty open slots show faint icons of the kinds of material ([screens](../interface/screens.md)).
- A formula is an ordered sequence of materials in the slots. The scripts compare the content of each slot to the stored formula, so the order of the materials matters.
- A sequence that matches no formula is a failed craft. The game remembers it and shows "not a mistake, but an experience. tap ANYWHERE to continue". A repeated failed sequence is recognised.
- Any craft spends the placed units when the player confirms the craft (author's confirmation). Closing the table without confirming returns them to the stock.
- A match shows "FORMULA FOUND! tap ANYWHERe to continue" and the piece becomes available. The screen shows a counter of found formulas out of 61, for example "1/61".
- The magnifying glass on the table shows the known scheme for the current materials.
- Examination during an operation reveals schemes of correct combinations. On the table the hint shows as marks in the slots: a drawn material for a revealed slot and a question mark for a slot that is not revealed ([operations](operations.md), [screens](../interface/screens.md)).
- Each formula uses from 1 to 6 units.

## Jewelry table

The table is taken from the script data. Columns:

- **Index:** the number of the jewelry piece, 1 to 61.
- **Script name:** the internal name used in the scripts. The pieces have no names in the game (author's confirmation), so these script names are not shown to the player.
- **Metals, Precious, Semi-precious:** units of each material the piece needs.

| Index | Script name | Metals | Precious | Semi-precious | Units |
|---|---|---|---|---|---|
| 1 | zazhim | 1 | 1 | 0 | 2 |
| 2 | koronka | 1 | 0 | 0 | 1 |
| 3 | microdermal | 0 | 0 | 1 | 1 |
| 4 | mushka | 0 | 1 | 0 | 1 |
| 5 | labret | 1 | 0 | 1 | 2 |
| 6 | shtanga | 2 | 0 | 0 | 2 |
| 7 | lense | 0 | 2 | 0 | 2 |
| 8 | bulavka | 2 | 0 | 1 | 3 |
| 9 | septum | 2 | 1 | 0 | 3 |
| 10 | kaffa | 3 | 0 | 0 | 3 |
| 11 | naperstok | 1 | 1 | 1 | 3 |
| 12 | kolco | 1 | 0 | 2 | 3 |
| 13 | kolco2 | 2 | 2 | 0 | 4 |
| 14 | tonnel | 0 | 0 | 3 | 3 |
| 15 | serga | 2 | 1 | 1 | 4 |
| 16 | brosh | 0 | 4 | 0 | 4 |
| 17 | kulon | 3 | 1 | 0 | 4 |
| 18 | sergi | 2 | 0 | 2 | 4 |
| 19 | persten | 1 | 3 | 0 | 4 |
| 20 | ochki | 1 | 1 | 2 | 4 |
| 21 | bracelet | 3 | 0 | 1 | 4 |
| 22 | chotki | 0 | 0 | 4 | 4 |
| 23 | garter | 4 | 0 | 0 | 4 |
| 24 | klipsa | 1 | 0 | 3 | 4 |
| 25 | naomi | 1 | 2 | 1 | 4 |
| 26 | choker | 0 | 2 | 2 | 4 |
| 27 | obruch | 3 | 2 | 0 | 5 |
| 28 | setka | 1 | 1 | 3 | 5 |
| 29 | greben | 2 | 3 | 0 | 5 |
| 30 | pheronierka | 0 | 5 | 0 | 5 |
| 31 | venok | 5 | 0 | 0 | 5 |
| 32 | korona | 4 | 1 | 0 | 5 |
| 33 | camea | 1 | 0 | 4 | 5 |
| 34 | medal | 2 | 1 | 2 | 5 |
| 35 | medalion | 2 | 2 | 1 | 5 |
| 36 | kolie | 1 | 3 | 1 | 5 |
| 37 | priazhka | 4 | 0 | 1 | 5 |
| 38 | rondel | 3 | 1 | 1 | 5 |
| 39 | busy | 0 | 0 | 5 | 5 |
| 40 | podveska | 1 | 2 | 2 | 5 |
| 41 | podveska2 | 3 | 0 | 2 | 5 |
| 42 | cep | 6 | 0 | 0 | 6 |
| 43 | ozherelie | 1 | 4 | 0 | 5 |
| 44 | poias | 2 | 0 | 3 | 5 |
| 45 | portupeia | 1 | 2 | 3 | 6 |
| 46 | sabaton | 2 | 2 | 2 | 6 |
| 47 | gulfik | 2 | 3 | 1 | 6 |
| 48 | naruchi | 4 | 2 | 0 | 6 |
| 49 | naplechnik | 4 | 0 | 2 | 6 |
| 50 | nabedrin | 4 | 1 | 1 | 6 |
| 51 | nakolen | 2 | 1 | 3 | 6 |
| 52 | nabedrennik | 5 | 0 | 1 | 6 |
| 53 | pektoral | 5 | 1 | 0 | 6 |
| 54 | metalcorset | 3 | 3 | 0 | 6 |
| 55 | hrebet | 0 | 6 | 0 | 6 |
| 56 | busy2 | 0 | 0 | 6 | 6 |
| 57 | colco2 | 1 | 1 | 4 | 6 |
| 58 | bracelet2 | 1 | 4 | 1 | 6 |
| 59 | nakladka2 | 1 | 5 | 0 | 6 |
| 60 | perchatka | 1 | 0 | 5 | 6 |
| 61 | sergi2 | 2 | 4 | 0 | 6 |

*The pieces have no names in the game (author's confirmation). The script names above come from the code only. A new piece is marked in the game by an open gold padlock on the result screen. The player may craft any piece, in any order.*
