# Bargaining

> Source note: the descriptions follow the Android APK build, the most current version. The PC build is slightly older. Exact numbers are not given: the game shows the player the values that matter.

Bargaining is the stage where a customer in the hall asks for a jewelry piece and the player picks services from a circle of 12 tools so that the price matches the customer's wallet. It is, together with the progression of crafting, the core of the game.

Related files: [README](../README.md), [day cycle](day-cycle.md), [operations](operations.md), [alchemy table](alchemy-table.md), [patron upgrades](../upgrades/patron-upgrades.md), [events](../events/events.md), [glossary](../glossary.md)

Screen title: "BARGAINING WITH A Customer", with the line "encrusting + SERVICES". The confirm button reads DEAL and shows the operation time in seconds. When there is no free operation table the button is replaced by a notice ([operations](operations.md)).

## Customers and wallets

- The hall is to the left of the workshop. Customers start to come once the player has crafted the first several pieces (author). Tapping the cloud at the feet of a customer opens the customer's screen ([screens](../interface/screens.md)).
- Each customer asks for one jewelry piece and has a wallet. The wallet is a little above the base price of the piece. Upgrades and events raise the wallet and the profit.
- Some customers come with a request for a piece the player has not unlocked yet but can already craft at the current stage: a padlock is shown in the cloud and the materials show "?".
- After successful installations customers with jewelry can come again (see below).

## The circle of 12 tools

The bargaining opens by tapping the scales on the customer screen. The tool buttons carry no captions; their pictures hint at what each service is (author). The element shows as a small icon on a button: green gem Earth, red gem Fire, blue gem Water, white pearl Air (author).

The circle holds 12 tools in four elements, three tools per element. The order of the elements repeats clockwise: Earth, Fire, Water, Air.

| Element | Effect |
|---|---|
| Earth | adds coins |
| Fire | gives a discount: a concession to the customer that frees room under the wallet for more services and bonuses (author) |
| Water | adds coins |
| Air | adds coins and reputation |

- Each customer gets different values on the tools, so the circle differs from customer to customer. How high the values can be depends on the number of open alchemy slots ([alchemy table](alchemy-table.md)).
- Every chosen tool adds time to the operation. The extra time differs by the time of day ([day cycle](day-cycle.md)).
- The tutorial text: "choose combinations of services to make better deals. some services are particularly expensive, some give discounts or add reputation".

## Matching the wallet

- A deal needs a price at or below the wallet, enough materials, a free operation table and a piece whose formula is found.
- When the price equals the wallet exactly, the screen shows "Perfect" and the reputation reward is doubled.

## Triangles

Three tools of one element chosen together make a triangle, drawn in yellow through the three buttons. The pattern (author): the bonuses differ and depend on the combinations the player chooses, and the game shows them to the player. The tutorial: "some services go well with others because they belong to the same element. stack triangles to get special bonuses to income, reputation or time". In general: Earth shortens the operation, Water raises the income, Air raises the reputation, Fire removes one mistake in the customer's requirements.

## Special requirements of customers (mobile build)

Some customers who come with progress have special requirements. Not every customer has them. The player should remember such a request when it is first opened.

- A banner states a requirement, for example that at least one service of an element is needed, or that the customer will not accept any service of an element (using it makes the customer leave).
- In the circle, an indicator by each element shows the state of the requirement: a dash means no requirement, a red "0/1" means at least one service is needed and not yet placed, "0/0" means the element is not allowed.
- The tutorial: "some customers definitely need a service of a certain element, sometimes even several. remember each request for a successful deal". Asking again is called unprofessional.
- A triangle of Fire removes one mistake in the requirements.
- Screenshots: [screens](../interface/screens.md).

## Returning customers

After successful installations customers with jewelry can come again. They need no serving and no bargaining: their cloud shows a thumbs-up hand. A tap gives resources at once, like a quick examination, and requires a free operation table ([operations](operations.md)).

## Waiting time and filth on the windows

- Each customer has a waiting time shown beside the heart icon on the customer screen (author).
- The cloud at the feet of a customer is the indicator of the waiting timer (author): white means that the customer still waits normally, rain and a storm mean that the patience is running out and the customer will soon leave angry and lower the reputation ([screens](../interface/screens.md)).
- A customer who is not served in time leaves filth on the window of the hall (author). The windows can be covered so thickly that the inspector is hard to see through them ([day cycle](day-cycle.md)).
- The death of the prisoner drives all customers away: they leave filth and the reputation drops (author; [basement](basement.md)).
- The tutorial: "serve the customers as quickly as possible while they wait patiently. A DISSATISFIED customer CAN cause trouble".
