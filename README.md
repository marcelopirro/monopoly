# Monopoly
Simplified version of the Monopoly made as an assignment for the Object Oriented Programming subject. Monopoly is a property buying and selling game where the objective is to acquire monopolies and make other players bankrupt.

## Rules
- 2 to 4 players;
- The order of the players is defined by rolling dice;
- All players start with $1500;
- The game has a linear and circular board, and the movement of the players is defined by the sum of the result of rolling two dice;
- If the player rolls a double (two equal dice) on the dice roll, he rolls again on the next round.
- If the player's balance reaches negative, he becomes bankrupt, having to hand over all properties to the bank and be removed from the game. If this occurs while paying another player, their properties go into your possession. All buildings are destroyed in this process.

## Spaces
### Starting Point
It's where players start. Whenever the player goes around the board and passes through this space again, he wins $200.

### Wealth Tax & Income Tax
They make the player pay an amount of money. In the case of the wealth tax, the amount is fixed and, in the case of the income tax, the player can choose between paying a fixed amount or a percentage of his wealth (money, properties and buildings).

### Card Space
The player draws a card from one of the game's dykes (vault and luck), which are randomized and dictate an action the player must take.

### Properties
Spaces that can be bought and traded by players and have a rent to be paid by players who land on them to the owner. They have three types:
- Lot: have one color. When all lots of a color belong to the same player, he gains the monopoly on that color, causing the rent on those lots to double. When the monopoly is conquered, the player can build a house on their lots (which increases the rent) and, when everyone has a house, a hotel that will replace the house.
- Utility: groups the electric company and the water distribution company. The rent depends on the value rolled on the dice and the amount of utilities the player has.
- Subway Station: the rent depends on the amount of stations the player owns.

On his turn, the player can make as many offers for someone else's property as he wants. If an offer on a monopoly lot is accepted, the player loses the monopoly and also the building (if any).

### Go to Jail
The player goes to jail.

### Chain
Where players are when they are trapped (if a free player lands on this space, nothing happens).

### Free Parking
Nothing happens in this space

## Prison
The player can be arrested if:
- Get three doubles in a row;
- Take the "go to jail" card;
- Fall into the "go to jail" space.

While in prison, he cannot receive rent, and to obtain release:
- 1st round arrested: can pay bail or try to take double;
- 2nd round arrested: can pay bail or try to take double;
- 3rd round trapped: you must try to take a double;
- 4th round arrested: must pay bail (if not possible, the player will go bankrupt).

## Victory
The player is declared the winner if:
- all others go bankrupt;
- get two monopolies;
- manage to build a hotel.

## Authors
- [Caike dos Santos](https://github.com/CaikeSantos)
- [Guilherme Bortoletto](https://github.com/guilherme-bortoletto)
- [Marcelo Pirro](https://github.com/marcelopirro)
- [Ryan Sakurai](https://github.com/ryansakurai)
- [Vinicius Castro](https://github.com/vinciuscastro)

(Computer Science Students at UFSCar)
