# Jewellirium

> **Source note:** the descriptions in this repository follow the Android APK build, which is the most current version of the game. The PC build is slightly older, so some details of it can differ. Exact numbers (prices, times, percentages) are not given: they change between builds, and the game shows the player the values that matter.

**Jewellirium** is a Renaissance-inspired roguelike game with a gloomy atmosphere. The player is the heir to a jewelry workshop that hides dark secrets. The player manages the workshop, performs operations on clients, and pursues the obsession no one else must know about: the Perfect Man, a human body fully encrusted with jewels.

- **Game title on the page:** JEWELLIRIUM game | Alchemy and jewelry craft
- **Developer:** Octanta Studio (Ukraine). Jewellirium is the studio's second game
- **Engine:** Unity
- **Genre:** roguelike with endless gameplay (author's description)
- **Languages:** English, Ukrainian (switched in Settings)
- **Platforms:** Android APK (the full and most current version); web browser on itch.io (a slightly older build); the itch.io page also lists a Windows archive
- **Release:** 2023 on mobile; moved to itch.io in 2026
- **Development and art:** Dariia Zodcha (Octanta Studio)
- **Music and sound design:** Shvetsb
- **Game page:** https://octantastudio.itch.io/jewellirium
- **Studio website:** https://www.octantastudio.com/
- **Family name of the workshop:** GIOIELLIERI, as it is signed on the letters
- **Controls:** taps and swipes on a touchscreen, clicks and mouse wheel on desktop. Yellow backlight or an outline shows where to act

## Core gameplay and additions

The core of the game (author's description) is two things: the progression of crafting jewelry, and trading with customers. In parallel the player feeds the prisoner and dodges the inspector. Everything else is an addition to this core.

| Part | What it is | File |
|---|---|---|
| Core | Crafting jewelry on the alchemy table: new formulas open new pieces | [mechanics/alchemy-table.md](mechanics/alchemy-table.md) |
| Core | Trading with customers: services from a circle of 12 tools, the price against the wallet, then the operation | [mechanics/bargaining.md](mechanics/bargaining.md), [mechanics/operations.md](mechanics/operations.md) |
| In parallel | Feeding the prisoner who makes the raw materials | [mechanics/basement.md](mechanics/basement.md) |
| In parallel | Closing the basement before the inspector comes | [mechanics/day-cycle.md](mechanics/day-cycle.md) |
| Addition | The showcase with passive income | [showcase/showcase.md](showcase/showcase.md) |
| Addition | The patron and his upgrades | [upgrades/patron-upgrades.md](upgrades/patron-upgrades.md) |
| Addition | The undertaker, marked customers, returning customers, special requests of customers | [characters/characters.md](characters/characters.md), [mechanics/bargaining.md](mechanics/bargaining.md) |
| Addition | Mail letters and special days | [events/events.md](events/events.md) |
| Addition (PC build only) | The ritual ring with magic stones | [rings/rings.md](rings/rings.md) |

## Premise

The workshop runs on two tracks. In the hall the player receives clients: crafts jewelry from metals and gems, bargains to stretch their budgets, and performs implantation operations. Deeper in the building a secret basement houses a prisoner who generates raw materials through alchemical synthesis. A letter from the previous master hands the workshop to the heir and entrusts the heir with the work on the Perfect Man. The last hint of the tutorial reads: "finish the perfect man at any cost".

The goal of the game, in the words of the game page: craft every possible piece of jewelry and complete the Perfect Man, a human body fully encrusted with jewels.

**The Perfect Man is assembled on the alchemy table (author).** The crafting screen is the process of assembling him: every formula the player finds fills in a scheme of the Perfect Man, and the progress is the counter of found formulas "x/61". The pieces unlock one by one through crafting, in any order. This progress is kept after a reset of the cycle. See [mechanics/alchemy-table.md](mechanics/alchemy-table.md).

## The loop of the game (author's description)

The game is an endless roguelike. A new day comes, new customers arrive. The player serves them, bargains, and in the breaks tries to craft new pieces of jewelry and feeds the prisoner, so that the resources suffice both for the operations and for the crafts. The player earns coins and reputation. New pieces can replace the old weak ones on the showcase for bigger passive bonuses at the end of the day. When the inspector comes, the player has to close the basement in time; otherwise he sees it, writes a fine and leaves.

## How a day works

1. **Time of day.** A day has four quarters (morning, day, evening, night). The sun clock at the top left shows them. At night customers and the inspector do not come, and the player can speed up time. See [mechanics/day-cycle.md](mechanics/day-cycle.md).
2. **Two rooms.** The hall is to the left of the workshop. The player moves between the workshop (alchemy table, basement, operation tables, mail) and the hall (customers, showcase, patron) by a swipe sideways on mobile or the mouse wheel on desktop.
3. **Basement.** The prisoner synthesizes metals, semi-precious stones or precious stones, whichever the player prioritises. His health runs down and has to be refilled with food or essences. See [mechanics/basement.md](mechanics/basement.md).
4. **Alchemy table.** The player combines materials in the slots until a formula is found. Found formulas open new jewelry. See [mechanics/alchemy-table.md](mechanics/alchemy-table.md).
5. **Customers.** Each customer asks for a jewelry piece and has a wallet. The player picks services from a circle of 12 tools so that the price matches the wallet. See [mechanics/bargaining.md](mechanics/bargaining.md).
6. **Operations.** After a deal the customer goes to an operation table. Operations run only while the basement is open, and an examination can reveal a hint of a new formula. See [mechanics/operations.md](mechanics/operations.md).
7. **Inspector.** The inspector visits during the day. A visit while the basement is open is a discovery. See [mechanics/day-cycle.md](mechanics/day-cycle.md).
8. **Night.** The showcase pays out, the mail is read, the player can order upgrades from the patron and speed up time.

## Progression

- **Within one workshop cycle:** days, coins, reputation, the prisoner, the showcase and the discovered schemes of the notes.
- **After three discoveries:** the cycle is reset: the days, coins, reputation, the prisoner and the showcase start again. The unlocked jewelry combinations are kept: this progress cannot be lost (author's statement). The exact values of the reset are not important. See [mechanics/day-cycle.md](mechanics/day-cycle.md).
- **Upgrades** come from the patron for coins and reputation: [upgrades/patron-upgrades.md](upgrades/patron-upgrades.md).

## Content warning (from the game page)

The game contains elements that some players may find disturbing: management of human test subjects, body modification and prosthetic implantation, alchemical experimentation on living tissue, and the pursuit of an obsession with no regard for its cost.

## Credits

- **Dariia Zodcha:** development and art.
- **Shvetsb:** music and sound design.

## Repository map

| Path | Content |
|---|---|
| `README.md` | this overview |
| [mechanics/day-cycle.md](mechanics/day-cycle.md) | time of day, night, mail, inspector, discoveries |
| [mechanics/bargaining.md](mechanics/bargaining.md) | customers, wallets, the circle of tools, elements, requests, returning customers |
| [mechanics/operations.md](mechanics/operations.md) | operation tables, examination |
| [mechanics/alchemy-table.md](mechanics/alchemy-table.md) | slots, formulas, the 61 jewelry pieces |
| [mechanics/basement.md](mechanics/basement.md) | prisoner, materials, food, essences, the undertaker |
| [characters/characters.md](characters/characters.md) | patron, undertaker, inspector, customers, senders of letters |
| [upgrades/patron-upgrades.md](upgrades/patron-upgrades.md) | the approximate list of upgrades |
| [rings/rings.md](rings/rings.md) | the ritual ring of the PC build |
| [events/events.md](events/events.md) | mail letters and special days |
| [showcase/showcase.md](showcase/showcase.md) | showcase slots, passive bonuses |
| [interface/screens.md](interface/screens.md) | the screens of the game with screenshots |
| [media/README.md](media/README.md) | list of screenshots |
| [glossary.md](glossary.md) | terms used across the files |
| [llms.txt](llms.txt) | short index of the pages for AI crawlers |
