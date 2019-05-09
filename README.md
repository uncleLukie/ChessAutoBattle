# ChessAutoBattle

Developed with Unreal Engine 4.22.0

A mobile game inspired by Auto Chess.

Game structure:
8 players enter an arena with a chess board each.
The game is played round by round.
It is survival of the fittest, every time you lose your health will be decreased by the number of enemy heroes + units left on the board after all of your heroes died. Once you reach 0 you are out of the game.
You can continue to spectate once dead or leave. Progress from the previous game and ranking will still be obtained even if you leave the game.


Economy:
Players gain income each round based on various factors.
There is a base income every round.
If a players wins the round they gain 1 gold.
If a player has a win streak of up to 3 wins in a row they get +3 gold every round.
If a player has a loss streak of up to 2 losses in a row they gain +2 gold.
For every 10 gold someone has they gain 1 gold every round up to 50+ gold giving 5 interest.


Heroes:
Each round you get a random selection of (5?) heroes to buy, bought heroes will be added to your sideboard. You can then drag these heroes onto your board.
Heroes are on a scale of tier 1 to 5 (1 being lowest). The higher the tier the more they cost and potentially more powerful they are.
If you have 3 of the same Hero of the same level you can combine them into one hero of increased level (up to level 3).
Heroes have a race and class. Races and classes have synergies for having additional races/classes on the board (e.g. having 3 different types of Hunters gives your Hunters extra damage across the board). Sideboarded heroes do not give you any effects, only active heroes on the board do.
Rerolls can be bought with gold which will give you a fresh set of random heroes to choose from.

Experience/lvls:
Players gain 1 exp every round.
Players can also buy experience using gold.

Creeps/items:
At the start of the game there are creep rounds that will have a random chance to drop a random item which you can equip on your heroes or keep for combination of a greater item later.
Every 5~ rounds there are creep rounds.

