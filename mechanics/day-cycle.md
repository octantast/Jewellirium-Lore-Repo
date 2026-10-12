# Day cycle

> Source note: the descriptions follow the Android APK build, the most current version. The PC build is slightly older. Exact numbers are not given.

The day cycle is the loop of the game: a day passes through four quarters, the night closes the day, and the mail, the inspector and the patron follow their own rhythms across days. Dodging the inspector is one of the two parallel tasks of the core gameplay (with feeding the prisoner, see [basement](basement.md)).

Related files: [README](../README.md), [bargaining](bargaining.md), [operations](operations.md), [basement](basement.md), [characters](../characters/characters.md), [events](../events/events.md), [showcase](../showcase/showcase.md)

## Quarters of the day

The day has four quarters: morning, day, evening and night. The clock at the top left of the screen shows them and the number of the day. The last quarter, the night, is the upper left one. The mirror of the sky at the lower right of the hall also shows the time of day: yellow is day, darker is evening and night, pinkish is morning. The mirror is not a button.

The speed of an operation depends on the quarter of the day: the extra services of a bargain add different amounts of operation time in different quarters. The details are shown to the player in the build.

## Time-lapse

A time-lapse button next to the clock speeds up the time, and pressing it again returns normal speed. It also speeds up the production of the basement. The speed-up is possible at night, and there is no condition for it (author).

## Night

- Customers stop coming and the inspector does not come at night.
- The showcase pays out coins and reputation once per day ([showcase](../showcase/showcase.md)).
- The undertaker can visit and bring a candidate for a new prisoner ([basement](basement.md)).
- The player reads the mail, orders upgrades from the patron and can speed up the time.

## End of the day

When the day ends, the day counter grows by one, the mail timer moves on, and the delivery of an ordered patron upgrade moves on. A new day starts.

## Mail

Letters arrive through a postman who walks through the hall; the letter button then slides out. There are story letters from the previous master (the first at the start of the game and the second after a reset caused by three discoveries) and event letters ([events](../events/events.md)).

## Inspector

- The inspector visits during the day. The tutorial text: the inspector visits the workshop every day, he has to be looked for in the windows, and he must not see the opened basement, otherwise a fine will be issued.
- **The walk (author's description):** the hall has four windows. The inspector starts behind the windows of the hall and moves from right to left, then enters the workshop. He can be noticed long in advance in the three far windows, then in the near window next to the vase, and then he walks slowly through the hall. So even with dirty windows the player can close the basement in time. When the basement is closed in time, he stands for a couple of seconds and leaves.
- Filth left by customers who were not served in time covers the windows and can hide him ([bargaining](bargaining.md)). With growing reputation more silhouettes of passers-by flicker behind the windows, which can slightly hinder spotting the inspector, but not by much.
- A visit while the basement is open is a **discovery**: the Council of Justice sends a warning letter with a penalty in coins.
- Screenshots: [screens](../interface/screens.md).

### Warnings and fines

| Discovery | Consequence |
|---|---|
| First | A fine in coins |
| Second | A fine in coins and a loss of reputation; the letter says it is the last warning |
| Third | The cycle is reset |

A period of days without penalties resets the count of warnings. The upgrade "blindness of justice" removes the fines ([upgrades](../upgrades/patron-upgrades.md)).

### Reset after three discoveries

After the third discovery the progress of the cycle is reset: the days, the coins, the reputation, the prisoner and the showcase start again. The unlocked jewelry stays: this progress cannot be lost (author). After the reset the second story letter arrives.

## Reputation and the street

Reputation changes how many customers come ("Low reputation cuts client flow", from the game page). Customers' reputation also shows in the street: more passers-by silhouettes behind the windows.

## The patron

When the player orders an upgrade, the patron brings it on a day shown on the screen. Only one order is active at a time. See [patron upgrades](../upgrades/patron-upgrades.md).
