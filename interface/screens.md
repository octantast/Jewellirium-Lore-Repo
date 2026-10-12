# Screens

> Source note: the descriptions follow the Android APK build, the most current version. The PC build is slightly older. Exact numbers are not given.

Screens of the game in the order the player meets them, taken from screenshots of the Android build in English. Each screen is confirmed by a screenshot; screenshots are in [media](../media/README.md).

Related files: [README](../README.md), [day cycle](../mechanics/day-cycle.md), [basement](../mechanics/basement.md), [alchemy table](../mechanics/alchemy-table.md), [characters](../characters/characters.md), [glossary](../glossary.md)

## Main menu

- The title "Jewellirium" is set in a round mirror-like gold frame on the left. The frame is decorated with red gems.
- Two buttons: **PLAY** and **SETTINGS**.
- The footer reads "PUBLISHED BY OCTANTA STUDIO" and "COPYRIGHT © 2023. ALL RIGHTS RESERVED".
- The background is a blurred view of the workshop.

## Settings

- **LANGUAGE:** ENG and УКР (English and Ukrainian). The chosen language is marked with a lit gold gem, the other with a dark one.
- **SOUND:** ON and OFF.
- **MUSIC:** ON and OFF.

## Start letter

- The first screen of a new game is a letter from the previous master. It opens over the workshop, which is shown in grey.
- The letter starts with a large red drop-cap M and reads "MY SON, NOW ONLY YOU ARE RESPONSIBLE FOR OUR JEWELRY WORKSHOP. FOR A LONG TIME I HAVE BEEN WORKING ON THE CREATION OF THE PERFECT MAN, WHOSE BODY WOULD BE COMPLETELY COVERED WITH JEWELRY. I DEVELOPED A DETAILED SCHEME AND PREPARED EVERYTHING FOR ALCHEMICAL EXPERIMENTS, BUT IN PRACTICE I COULD NOT FIND WORKING FORMULAS. I ENTRUST THIS TASK TO YOU." It is signed GIOIELLIERI.
- A drawing beside the text shows a ring with a stone above it and a pin that goes into a red-stained surface.
- The letter is decorated with a cross at the top.

## Interface elements visible behind the letter

Behind the start letter the interface already shows: a counter of coins (a coin with a pentagram) and a counter of reputation (a golden cup) at the left, and three resource drawers at the right: precious stones (red gem), semi-precious stones (green stone) and metals (white ore).


## Tutorial with the hand from the cloud

After the start letter the tutorial begins on the first launch. A hand that reaches out of a white cloud points at the part of the screen the player has to use. The pointed element gets a yellow highlight. Instructions appear in a dark red banner with a gold frame at the top of the screen. The workshop is shown in grey with the master, a man in dark clothes who works at a bench on the left.

| Step | Banner text | What the hand points at |
|---|---|---|
| 1 | "CHOOSE WHICH RESOURCES TO SYNTHESIZE FOR WORK. THEY WILL BE CREATED HERE AUTOMATICALLY OVER TIME" | the three resource drawers on the right (precious stones, semi-precious stones, metals), highlighted in yellow |
| 2 | "KEEP THE BASEMENT OPEN SO THAT EXPERIMENTAL RAW MATERIALS ARE AT HAND" | the eye icon, which opens and closes the basement; the drawer of semi-precious stones is shown enlarged and lit, the drawer of metals dimmed |
| 3 | no banner visible on the screenshot | a framed object at the top right, the eye icon near the glassware on the floor and the alchemy table (the scroll with the ring diagram), all outlined in yellow |
| 4 | "KEEP THE PRISONER ALIVE TO CONTINUE SYNTHESIZING RESOURCES. DON'T LET HIM DIE AT THE MOST INOPPORTUNE MOMENT" | the DEAL button of the prisoner screen (see below) |

- The eye icon opens and closes the basement (author's confirmation). An open basement is needed for operations and is what the inspector must not see ([basement](../mechanics/basement.md), [day cycle](../mechanics/day-cycle.md)).
- The scroll with the ring diagram on the table is the alchemy table ([alchemy table](../mechanics/alchemy-table.md)).
- Objects of the workshop outlined in yellow are buttons. Each opens its own screen (author's confirmation). The hand from the cloud points at them in turn.
- The banner text of step 3 is not confirmed yet.
- The sun clock at the top left shows a growing wedge on the third screenshot, so the day timer already runs during the tutorial.

## Prisoner screen (feeding)

- **How to open it:** the crate that rises and lowers in the hidden basement is a button. The lift stands in a recess of the wall behind the cabinet at the upper right of the workshop, a hidden descent down; on the screenshots the recess shows as a dark rectangle. The lift button is hidden while the basement is closed (author's confirmation). Pressing it opens the prisoner screen in the basement below (author's confirmation). On this screen the player chooses what to put into the prisoner: food or essences (elixirs).
- **Title:** "FEEDING THE PRISONER" with a large drop-cap F.
- **Left:** a framed portrait of the prisoner, a kneeling figure with gems set in his body and a bowl in front of him. Beside the portrait is a vertical health scale. A heart icon next to it shows his health in seconds (159S on the first screenshot, 213S on the second).
- **Right:** three framed offers side by side. The left frame shows one bottle with a glass, the centre frame shows a jug with food (apple, bread, cheese, meat, rice), the right frame shows several bottles. The chosen frame is highlighted in yellow.
- **Below the offers:** the name of the chosen offer ("BOWL FULL OF FOOD"), its effect next to a second heart icon ("+60S"), the price with a coin icon ("-20") and the DEAL button with a wax seal.
- **Result of a deal:** the second screenshot shows the screen during the animation after the deal: the coin counter falls and the health counter rises.
- The resource drawers stay visible on the right. On both screenshots the drawer of semi-precious stones is lit and its count is 4 (it was 3 before), so the prisoner has produced one semi-precious stone.
- The tutorial hand from the cloud points at the DEAL button on the first screenshot.
- **Essences:** elixirs are bought on this screen as well (author's confirmation). The left frame is one essence and the right frame is several essences.

| Offer | Name on the screen | Effect shown | Screenshot |
|---|---|---|---|
| Left frame | ESSENCE OF GROWTH AND STRENGTHENING | a few resources of the priority kind | `prisoner-essence-one.jpg` |
| Right frame | ESSENCES OF GROWTH AND STRENGTHENING | many resources of the priority kind | `prisoner-essences-many.jpg` |
| Centre frame | BOWL FULL OF FOOD | refills the health | `tutorial-4-prisoner-feeding.jpg` |

- The icon and the number of the reward follow the resource that is set as the priority. With semi-precious stones as the priority the bottles are teal and one essence gives +1; with precious stones as the priority the bottles are red and several essences give +7.
- The chosen frame is highlighted in yellow and the other two are shown in grey.

## Resource drawers

- The three drawers on the right of every screen hold the resources: precious stones (red gem), semi-precious stones (green stone) and metals (white ore). The resources are generated over time (author's confirmation).
- Pressing a drawer sets the priority of generation to that resource (author's confirmation). The prioritised drawer is lit and the other drawers are dimmed.

## Alchemy table screen

- **How to open it:** in the workshop the scroll with the ring diagram on the table is the button (outlined in yellow, the hand from the cloud points at it on `tutorial-5-alchemy-table-button.jpg`).
- **Background:** pale anatomical drawings in the manner of a man with spread arms on both sides, with faint red stains.
- **Tools on the table:** a magnifying glass in a decorated frame at the bottom right (the hand points at it in the tutorial), and drawn instruments around the edge (pincers, scissors, a ring-shaped tool, a blade).
- **Placing a unit:** on `alchemy-table-stone-placed.jpg` a stack of green stones lies in the bottom-right slot and the count of semi-precious stones fell from 4 to 3. A placed unit leaves the stock.
- **Padlock:** an open gold padlock at the bottom right of the result screen means that a new piece of jewelry has been unlocked (author's confirmation).

## Craft of a second piece (random combination)

The author shows a second craft made from a random combination. The player may craft any piece in any order.

2. **Craft animation** (`craft-2-animation.jpg`): the magnifying glass appears in the centre inside a circle of black rune-like signs. An orange fire ring runs around it, and a red brush stroke curves inside. The counter has changed to 2/61. The signs cannot be read on the screenshot.

- The craft spent the placed units: the counts of semi-precious stones and metals (2 and 8) stayed the same after the craft as after the placing. The count of precious stones rose from 1 to 2 because the prisoner generates the chosen type of resource while he is alive.
- The sun clock at the top left shows a growing wedge on all three screenshots.

## Hall and customers

- **Where:** the hall is to the left of the workshop (author's confirmation). Customers stand in the hall (`hall-customers.jpg`).
- **When customers come:** as soon as the player has crafted the first several pieces of jewelry, customers start to come (author's confirmation).
- **Requests:** customers have requests (author's confirmation). See [bargaining](../mechanics/bargaining.md).
- **Clouds:** a small cloud with a hand that reaches out of it lies at the feet of each customer. The clouds are outlined in yellow. Tapping the cloud of a customer opens that customer's screen (author's confirmation).
- **The cloud as a timer indicator (author's confirmation):** the clouds show the waiting timers of the customers. A white cloud means that the customer still waits normally. A cloud with rain and a storm (dark, with lightning and drops) means that the patience is running out: the customer will soon leave angry and lower the reputation ([bargaining](../mechanics/bargaining.md)).
- **The round mirror (author's confirmation):** the round frame with a window at the lower right of the hall is not a button. It is a mirror that reflects the sky and shows the time of day: yellow is the day, darker is the evening and the night, and the morning is pinkish.
- **The scene:** three customers stand in a tiled hall with columns and windows: a woman in a headscarf, an older woman with her hands on her hips and a man in a doublet with his hand on his hip. A white cabinet stands at the left edge. The tutorial hand from the cloud points at the customers.

## Customer screen

`customer-screen-tutorial.jpg` shows the screen of one customer on its first opening.

- **Title:** "Bargaining with a Customer" with a large drop-cap B. Under the circle of tools the line reads "ENCRUSTING + SERVICES".
- **Tutorial banner:** "THE CUSTOMER WANTS TO GET JEWELRY FROM GIOIELLIERI. THE OPERATION WILL REQUIRE STONES AND A FREE TABLE." A third sentence says that a successful operation pays well and does not harm the master's reputation. The family name is written GIOIELLIERI here.
- **Left:** a portrait of the customer (a woman with a bead necklace holding a note), a grey thought cloud above her with a small piece of jewelry in it, a purse with the number 15 (the wallet of the customer) and a heart icon with the number 51S beside the vertical scale. It shows the waiting time of the customer (author's confirmation). It is the same kind of indicator as the health of the prisoner on the feeding screen.
- **Right:** a circle of round tool buttons around a pair of scales over an open book. Each button shows a hand and a number with a plus (+1, +2, +4, +5 are visible; part of the circle is hidden under the banner). The scales are outlined in yellow and the tutorial hand points at them.
- **Offer line:** a coin icon with +10 and a cup icon (reputation) with a dash.
- **Requirements row:** four icons with values: precious stones (red gem) a dash, semi-precious stones (green stones) -1, metals a dash, tables 1. So the operation needs one semi-precious stone and one free table.

## Bargaining screen

- **How to open it:** tapping the scales on the customer screen opens the bargaining (author's confirmation). The first screenshot of the batch repeats the customer screen with the tutorial hand pointing at the scales.
- **Aim:** the player piles up services while their cost does not exceed the wallet of the customer (author's confirmation).
- **Tutorial banner:** "THE CUSTOMER HAS MORE MONEY IN HIS WALLET THAN IS NEEDED FOR ONE PIECE OF JEWELRY. OFFER HIM ADDITIONAL SERVICES TO MAKE A MORE PROFITABLE DEAL, BUT ALSO A LONGER ONE" (`bargaining-tutorial.jpg`).
- **The scales:** a coin with the current sum stands on the left pan (+10 at the start) and the purse with the wallet (15) stands on the right pan.
- **The circle:** 12 round buttons around the scales. Each button shows a hand performing an action, a small icon on top and a number at the bottom with a plus or a minus. The services have no captions (author's confirmation), the pictures only hint at what they are. Each additional service has its own price and its own element, and combinations give bonuses (author's confirmation; see the triangles in [bargaining](../mechanics/bargaining.md)).
- **Element marks seen on the buttons:** the small icon on top of a button is a green gem, a red gem, a blue gem or a white pearl, three buttons of each. The buttons of the elements carry numbers with a plus (income) or a minus (Fire, the discount); the white pearl buttons have a small cup beside them (reputation).

- **Choosing services:** a chosen button is highlighted and its background takes the colour of its element (`bargaining-perfect.jpg`: the green +3 and the blue +2 are chosen).
- **Perfect:** with +3 and +2 chosen the sum on the left pan is +15, equal to the wallet of 15. The word PERFECT appears at the bottom and a burst with "X2" appears beside the reputation cup. The tutorial hand then points at the DEAL button.
- **Waiting time at the top:** during the bargaining the waiting time of the customer is shown at the top.
- **DEAL button:** it reads DEAL and the operation time in brackets, in seconds.
- **After the bargaining** (`customer-screen-after-bargain.jpg`): the customer screen shows the offer +15, reputation with a dash, the requirements row (semi-precious stones -1, table 1) and the DEAL (10S) button. The tools sit in a small circle with the chosen ones lit. A hand from a cloud with a raised thumb is drawn over the circle.

## Bargaining: hints for combinations

The author shows the tutorial hints inside the bargaining screen of a second customer: a woman in a headscarf, with the drawing of the two-prong piece (the piece from the second craft) behind her. The wallet is 26 (the purse on the right pan).


1. **The triangle** (`bargaining-trine-tutorial.jpg`):
   - A yellow triangle runs through the three Water buttons (). The same triangle is drawn on the next three screenshots. No button is chosen here.
2. **The discount** (`bargaining-fire-tutorial.jpg`):
   - The three Water buttons are chosen and coloured blue. The sum on the left pan is red: above the wallet.
   - The banner reads "YOU OFFER MORE THAN THE CUSTOMER CAN AFFORD. HE DOESN'T HAVE THAT MUCH MONEY IN HIS WALLET. GIVE HIM A DISCOUNT USING FIRE". The hand from the cloud points at the Fire button -3 at the bottom right, which is outlined in yellow.
3. **Fire chosen** (`bargaining-water-fire-chosen.jpg`):
   - The Fire button -3 is chosen and coloured red. The sum is brown (not above the wallet). The DEAL button appears.
4. **Perfect with Air** (`bargaining-perfect-air.jpg`):
   - The Air button +1 is chosen as well. The sum is +26, equal to the wallet. The word PERFECT is at the bottom, a burst "X2" stands beside the reputation cup, and the cup indicator shows +2. The DEAL button reads "DEAL (12S)", the waiting time reads 46S.


Observations and the author's answers:

## Death of the prisoner

The author describes a game situation: the prisoner dies when the player forgets to feed him for a certain time. The sequence on the screenshots:

1. **Workshop with the stopped synthesis** (`prisoner-death-workshop.jpg`):
   - The author's statement: the spawn of resources stops, the resource crate is red and its timer stands.
   - The top drawer has a red background and the semi-precious drawer shows a dash instead of a number.
   - The master works at the bench on the left, the eye icon is lit in yellow at the right, and an envelope with a gold seal outlined in yellow lies on the table at the bottom.
2. **The hall with the death merchant** (`prisoner-death-undertaker-hall.jpg`):
   - The author's statement: all customers are driven away, they leave filth on the windows and the reputation drops, because the undertaker walks into the hall. He leaves a new prisoner of the base level. Then the spawn resumes and the customers come again.
   - The screenshot shows no customers in the hall. A figure in a black hooded cloak with a long beard and a staff walks between the columns and carries a white bundle in the crook of his arm. The drawer at the top still has the red background.
3. **The feeding screen with the new prisoner** (`prisoner-new-feeding-screen.jpg`):
   - The screen is titled "Feeding the prisoner". The prisoner kneels in the frame at the left, covered with gems, with an empty bowl on the floor. The health of the prisoner reads 351S beside the heart. The three arches are as on the other feeding screenshots, the middle one (the bowl of food, +60S, -20 coins) is chosen and the DEAL button is lit.
- The sun clock shows the same wedge on all three screenshots, which agrees with the author's statement that the timer stands.

## Inspector

- The hall has four windows.
- The inspector begins his walk behind the windows of the hall, from right to left, and then enters the workshop.
- He can be noticed long in advance in the three far windows, then in the near window next to the vase, and then he walks slowly through the hall.
- Because of this, the player can close the basement in time even with dirty windows.
- When the basement is closed before he arrives, he stands for a couple of seconds and leaves.

The screenshots:
2. **Tutorial banner** (`inspector-tutorial-hall.jpg`):
   - Three customers stand in the hall, the clouds at the feet of two of them show rain and lightning. The legs of a walking figure show behind the columns at the top, under the banner.

## Clock of the day, evening and night

- **The clock (author's confirmation):** the sun clock at the top left shows the time of day. It is divided into four quarters. The last quarter, the night, is the upper left one.
- **Evening** (`workshop-clock-evening.jpg`):
  - The workshop shortly before the night. Late in the day customers stop coming, and the inspector does not come at night (author's statement; [day cycle](../mechanics/day-cycle.md)). The author says it is a good moment for the letters of the patron, which the still starting tutorial hint leads to.
  - Objects outlined in yellow: the scroll with the ring diagram (the alchemy table), the envelope with a gold seal on the table (the mail), the eye icon, and the dark rectangle at the upper right, to the left of the shelves. It is the recess in the wall behind the cabinet, the hidden descent down, and the lowering lift stands in it. The lift: a button that opens the prisoner screen for passing food down (author's confirmation; see "Prisoner screen"). The lift button is hidden while the basement is closed, so its outline on this screenshot shows that the basement is open.
- **Night tutorial** (`night-tutorial-mail.jpg`):
  - The hand from the cloud points at the envelope on the table (outlined in yellow), and the scroll is outlined as well.
  - A yellow arrow button lies over the sun clock at the top left. It is the time-lapse button (author's confirmation). The author states that the time can be sped up at night in general: there is no condition for it, the night is simply the time when it is possible to go faster ([day cycle](../mechanics/day-cycle.md)).
- **The hall at night** (`hall-night.jpg`):
  - The hall is empty: no customers and no clouds at the floor. The author states that customers stop coming late in the day.
  - The whole picture is darker and bluish: the floor tiles, the columns and the walls are in dim grey and blue tones.
  - The mirror of the sky at the lower right is dark blue with a faint star, which shows the night (author: darker is the evening and the night).
  - The sun clock at the top left has a dark blue part at its left side, and the yellow arrow button (time-lapse) lies over it.
- **The envelope (author's confirmation):** the envelope on the table is the button of communication with the patron. The patron brings upgrades to the workshop and to the hall for resources (see "Patron's offer").

## Patron's offer

The envelope on the workshop table opens the screen of the patron (author's confirmation). The patron brings upgrades to the workshop and the hall for resources; the screen shows the cost in coins and in reputation.

- **The scene:** at the left a framed picture of a winged old man who pours gold coins from his hand onto a heap of coins. The title "Patron's offer" stands at the bottom left. Three arches in gold frames stand at the right, each with a drawing of one upgrade on a scroll. The tutorial hand from the cloud points at the price of coins.
- **The arches and the offers:** three upgrades are on offer at a time. The screenshots show an alchemy table light (glass cylinder with a candle, middle arch), showcases and entourage of the hall (a table, left arch; the icon says "+1 SLOT"), and "Blindness of justice, no fines" (a blindfolded figure with a sword, right arch).
- **Prices:** every offer shows a price in coins and a price in reputation. A price in red is above what the player has, a price in brown is affordable. The coin price is spent on the order; the reputation price is only a requirement. The DEAL button appears when both prices are affordable, and shows the days the delivery takes.
- **One order at a time:** after an upgrade is ordered, its picture gets a RESERVED seal, the other arches are dimmed and cannot be bought until the patron brings the current one. The bottom of the screen then says that the upgrade will be delivered on a certain day (`patron-order-reserved.jpg`). Before the order the same screen shows both prices and the DEAL button (`patron-order-day2.jpg`).
- Upgrades and their effects: [patron upgrades](../upgrades/patron-upgrades.md).

## A new day: the hall in the morning


## Bargaining without a free table

- **Screenshot** (`bargaining-no-free-tables.jpg`): the bargaining screen of a customer, a woman in a headscarf, with the drawing of the two-prong piece behind her.
- **Chosen:** several buttons of different elements, so that the sum equals the wallet. PERFECT is at the bottom and the burst X2 stands beside the cup.
- **No free table:** instead of the DEAL button the screen shows the text "NO FREE TABLES" at the lower right. In the requirements row at the bottom the value of the table is red. So the deal cannot be made while all operation tables are occupied ([operations](../mechanics/operations.md)).

## Craft of a piece from three units

1. **Empty table** (`alchemy-table-3-of-61-empty.jpg`): the counter reads 3/61. The three upper slots carry red seals. The three open slots at the bottom show faint icons of the kinds of material: a diamond at the bottom left, a round stone at the bottom centre and a lump of ore at the bottom right. The drawers are expanded and show the labels PRECIOUS STONES 5, SEMI-PRECIOUS STONES 4, METALS 4. The player has 203 coins and 20 reputation.
3. **Result** (`alchemy-table-formula-found-4.jpg`): the counter reads 4/61. A white glow shows a drawing of two long parallel prongs on a bent base with a gold setting and a lilac crystal on the top of one prong. The message "FORMULA FOUND! TAP ANYWHERE TO CONTINUE" is at the bottom and the open gold padlock is at the lower right.

## Inspector: the walk and the fine

3. **The warning letter** (`warning-letter-council.jpg`):
   - A large sheet with the title "Warning" and the eye emblem. The text, in a paraphrase: the Council of Justice writes that the crimes committed in the basement of the GIOIELLIERI workshop must be stopped; this time the council turns a blind eye to them to prevent unrest in the town; the punishment will be severe when nothing changes in the near future. Below stand "PENALTY -150" with a coin stamp and the signature "COUNCIL OF JUSTICE". "SWIPE UP ANYWHERE TO CLOSE" is at the bottom.
4. **After the fine** (`inspector-workshop-after-fine.jpg`): the inspector stands in the middle of the workshop with a hand at his chin, with the cloud and the pointing hand in front of him. The coins read 105: the fine of 150 was taken (255 - 150). The reputation is still 25. The eye icon is outlined in yellow, the lift frame is not outlined. A small letter with a gold seal lies on the table next to the other letters.

## Operation and examination

- **The operation table:** a customer who is taken for service occupies a bed, an operating table, in the workshop (author's confirmation). On `operation-examination-cloud.jpg` the customer lies on the table at the top right of the workshop, near the curtains, while the master works at the bench on the left.
- **Materials are spent at the deal:** the count of semi-precious stones fell from 2 to 1 between the bargaining screenshots and this one, which matches the requirement of one semi-precious stone shown on the customer screen ([bargaining](../mechanics/bargaining.md)).
- **The examination cloud:** a small cloud with a hand holding a drawing instrument appears above the table and is outlined in yellow. It appears at random and has to be tapped quickly (author's confirmation). The tutorial hand from the cloud points at it.
- **Meaning:** a tap means that an idea of a new piece of jewelry came during the operation. A blueprint hint of the new formula then starts to assemble on the alchemy table (author's confirmation).
- **After the tap** (`operation-cloud-tapped.jpg`): the cloud above the table is shown larger with a sun-like emblem, the tutorial hand points at the alchemy table (outlined in yellow, with sparkles), and the count of precious stones rose to 3 with a ring of sparkles around its drawer.
- **The hint on the table** (`alchemy-table-examination-hint.jpg`):
  - The three open slots at the bottom of the table now show marks: the bottom-right slot shows a faint drawing of a piece of ore, and the bottom-left and bottom-centre slots show a question mark.
  - The author reads this hint as: the new formula will begin with a metal. The question marks stand for the materials that are not revealed yet.
  - The slots fill clockwise from the bottom-right slot (author's confirmation; see [alchemy table](../mechanics/alchemy-table.md)), so the bottom-right slot is the first slot of the formula.
  - The formula that the hint led to has one unit: the author crafted the piece from one metal (see the next section). The question marks therefore do not show the length of the formula.

## Craft by the hint

- **Result** (`examination-formula-found.jpg`): the author followed the hint and crafted a piece from one metal. The screen shows the message "FORMULA FOUND! TAP ANYWHERE TO CONTINUE", the examination tutorial banner and a white glow with a drawing of a white lump of ore with a gold arc above a drawing of an eye. The author describes the piece as a holder for an eyebrow (author's words). The open gold padlock is at the bottom right.
- **Slots on the screenshot:** the top-left and top-right slots carry red seals, the bottom-left slot shows a question mark, and sparkles lie around the slots.

## Tutorial hand toward the showcase

- **Screenshot** (`hall-tutorial-hand-left.jpg`): the hall with the same three customers, each with a cloud outlined in yellow at the feet. The tutorial hand from the cloud at the top left now points to the left, away from the customers. A white cabinet stands at the left edge.
- **Author's statement:** after the hint craft the tutorial leads to the showcase, because several pieces are unlocked and the player can put them on display.

## Showcase screen

The showcase is described in [showcase](../showcase/showcase.md). The screenshots:

1. **Tutorial** (`showcase-tutorial.jpg`):
   - The screen is titled "Showcase design" (decorated letter S at the bottom left).
   - A scroll with rows hangs at the left. Each row has a gold-framed red square at its left and an empty light-blue cell at its right. Two rows are fully visible, the first row is partly covered by the banner.
   - A gold frame in the middle of the right half is outlined in yellow and holds the drawing of the piece from the second craft (two long prongs on a bent base with an hourglass emblem). The tutorial hand from the cloud points at it. A small drawing of a crystal lies on the wall at the fingertip of the hand.
   - Three indicators run along the bottom: scales with a heart, a coin with a pentagram and a cup. All three show a dash.
2. **One piece placed** (`showcase-one-placed.jpg`):
   - The prongs piece now sits in the first row of the scroll, in the cell outlined in yellow.
   - The gold frame holds the drawing of the piece from the first craft (a crystal on white ore). A faint drawing of the new eyebrow piece lies on the wall to the left of the frame.
   - The three indicators show the bonuses of the placed pieces.
   - A text at the bottom reads "MONEY AND REPUTATION WILL BE RECEIVED BY THE END OF THIS DAY".
3. **Two pieces placed** (`showcase-two-placed.jpg`):
   - The prongs piece is in the first row, the eyebrow piece is in the second row (cell outlined in yellow). The faint drawing at the left of the frame is gone. The frame still holds the crystal piece.
   - The three indicators show the bonuses of the placed pieces.
   - The precious stones count is 4 (it was 3), the other drawers are unchanged.

What the author states (all confirmed):
- The pieces on the showcase generate a resource at the end of the day. The player chooses which pieces to take off and which to put on.
- **The right half is the strip of unlocked pieces.** The player swipes the strip, and a tap on the chosen piece in the gold frame puts it on the showcase.
- **The left scroll holds the showcase slots.** A tap on a piece that sits on the showcase clears its slot, and the piece returns to the collection.
- The showcase starts with 3 open slots and 3 closed slots, which open through upgrades. The scroll shows only the 3 open rows on these screenshots.
- The order of filling the slots does not matter.
- The first indicator (scales with a heart, the value in seconds with the letter S) is a bonus to the waiting time of customers: with a full showcase the customers admire it and stay longer.
- Every piece gives its own bonuses: its own coins, its own reputation and its own waiting-time bonus. Which piece gives which value does not matter for the documentation of the screen.

Observations from the screenshots:
- The text on the screen names money and reputation as what is received by the end of the day. The indicators changed as pieces were placed.
- The pieces placed on the screenshots are the piece from the second craft (two prongs on a bent base) and the eyebrow piece. The crystal piece from the first craft stays in the strip.

## Special requirements of customers (mobile build)

Some customers who come with progress have special requirements at the bargaining. Not every customer has them. The player should note it the first time such a request is opened.

- **A required element:** the red banner reads that at least one service of an element is needed (`bargaining-water-required.jpg`). In the circle the indicator of that element shows a red "0/1" (a service is needed and not placed yet) (`bargaining-water-required-after.jpg`).
- **A forbidden element:** the banner reads that the customer will not accept any service of an element, and the drop of that element on the scales is crossed out (`bargaining-water-forbidden.jpg`). Using such a service makes the customer leave. In the circle the indicator shows "0/0" (`bargaining-water-forbidden-after.jpg`).
- **No requirement:** the indicator of an element shows a dash.
- The requirements work together with the usual rules of the circle: [bargaining](../mechanics/bargaining.md).

## Request for a piece that is not unlocked yet

A customer can come with a request for a piece the player has not unlocked but can already craft at the current stage. The cloud of the customer shows a gold padlock, the materials of the bargaining show "?" instead of numbers, and the scales are still empty (`bargaining-locked-request.jpg`). The piece itself is shown to the player after the unlocking.

## Returning customers

After successful installations customers with jewelry can come again. They need no serving: their cloud shows a thumbs-up hand. A tap gives resources at once, like a quick examination, and needs a free operation table. Such customers are visible on `hall-returning-customer-day3.jpg` and `hall-marked-customer-day3.jpg`. See [operations](../mechanics/operations.md).

## The undertaker: letter and marking (from day 2, mobile build)

- **The letter** (`undertaker-letter.jpg`): on day 2 the undertaker Nefario sends a letter about himself. Its effect line reads that unusual customers appear, including those sent by the inspector. The letter closes by swiping up.
- **Marking** (`undertaker-mark-tutorial.jpg`): a hint asks the player to put a mark on a customer. A hand from a cloud touches the head of the customer. During the day he is watched, and at night the player receives information about him.
- **Confirming** (`undertaker-mark-confirm.jpg`, `undertaker-mark-confirm-raven.jpg`): until the customer leaves, the mark can be removed. The choice is confirmed only when he leaves. A raven sits on the marked customer. The hint says it is better not to serve him, so as not to arouse suspicion.
- **Result:** the undertaker scouts the marked customer and brings him at night as a candidate for a new prisoner, together with other options. See [basement](../mechanics/basement.md).

## Passer-by silhouettes

With the growth of reputation more silhouettes of passers-by flicker behind the hall windows. This can slightly hinder spotting the inspector.
