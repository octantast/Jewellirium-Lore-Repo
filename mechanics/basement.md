# Basement

> Source note: the descriptions follow the Android APK build, the most current version. The PC build is slightly older. Exact numbers are not given.

The basement is the hidden room where a prisoner synthesizes the raw materials of the workshop. It has to stay open for operations to run, and an open basement is what the inspector must not see. Feeding the prisoner is one of the two parallel tasks of the core gameplay (with dodging the inspector, see [day cycle](day-cycle.md)).

Related files: [README](../README.md), [day cycle](day-cycle.md), [operations](operations.md), [alchemy table](alchemy-table.md), [characters](../characters/characters.md), [patron upgrades](../upgrades/patron-upgrades.md), [glossary](../glossary.md)

## Synthesis

The prisoner generates the chosen type of resource for as long as he is alive (author).

- The three drawers on the right of the screen hold the resources: precious stones, semi-precious stones and metals. Pressing a drawer sets the priority of generation to that resource ([screens](../interface/screens.md)). The tutorial: "choose which resources to synthesize for work. they will be created here automatically".
- "keep the basement open so that experimental raw materials are at hand".
- An upgrade doubles the extraction of resources ([patron upgrades](../upgrades/patron-upgrades.md)).

## Prisoner health

- The prisoner's health runs down with time (and faster in the time-lapse). It has to be refilled with food or essences.
- A higher level of the prisoner means more maximum health and a faster synthesis of more kinds of resources.
- When the health is gone, synthesis stops and the undertaker is called. The tutorial: "keep the prisoner alive to continue synthesizing resources. DON'T LET HIM die at the most inopportune moment".

## Death of the prisoner (author's description)

- The prisoner dies when the player does not feed him for a certain time.
- The spawn of resources stops: the resource crate turns red and its timer stands.
- All customers are driven away. They leave filth on the windows and the reputation drops, because the undertaker walks into the hall.
- The undertaker leaves a new prisoner of the base level. This is separate from his selling of prisoners, which continues (author). The spawn then resumes and the customers come again.
- Screenshots: [screens](../interface/screens.md).

## Feeding

The screen is titled "FEEDING the prisoner" and has three offers. It is opened by the lowering lift (a hidden descent in a recess behind the cabinet); the lift button is hidden while the basement is closed (author) ([screens](../interface/screens.md)):

| Arch | Offer | Effect |
|---|---|---|
| Left | ESSENCE OF GROWTH AND STRENGTHENING (one) | immediate resources by priority |
| Centre | BOWL FULL OF FOOD | refills the health |
| Right | ESSENCES OF GROWTH AND STRENGTHENING (several) | more immediate resources by priority |

- Food and essences cost coins.
- Essences raise an essence scale; too much of it harms health. The tutorial: "essences affect the balance of fluids in the body and are addictive. it is better not to drink them too often".
- The food option is unavailable when health is already at maximum.

## The undertaker and the prisoner levels

The undertaker (the death merchant) sells prisoners of higher levels. The labels in the game: level 2 HOPELESS TRAMP, level 3 NAIVE FOREIGNER, level 4 OUTLAW FROM THE SUBURBS. The screen is titled "RAW MATERIAL SUPPLY". The prices rise with the level of the prisoner (the player sees them in the build).

**Marking (mobile build, from day 2):** the undertaker sends a letter about himself. Then the player can put a mark on a customer in the hall. The undertaker watches the marked customer during the day, scouts him, and brings him at night as a candidate for a new prisoner, together with other options. The mark can be removed until the customer leaves; the choice is confirmed when he leaves. The hint says it is better not to serve the marked customer, so as not to arouse suspicion ([screens](../interface/screens.md)).

## Discovery

A visit of the inspector while the basement is open is a discovery ([day cycle](day-cycle.md)).
