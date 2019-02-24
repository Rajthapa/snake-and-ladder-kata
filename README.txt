# snake-and-ladder-kata
The game code was produced  using Visual studio. The code is based on C# programming language.
The application allows 2 players to take part and each of them gets their turn to roll a dice.
The application allows system to display random number between 1 to 6 every time when the dice is rolled.
The token moves across the board based on the random number displayed by the dice once rolled and carries on until one of the player is on final square.
Suppose the token is on square 1. The dice displays number 3 when rolled. The application then moves the token 3 spaces further from square 1 to square 4. Technically, it sums up (1+3 is 4). To implement it, switch/break statement were used on C#. 
A ladder is placed on square 4 so that when token is on square 4 it allows token to jump to the square 8. On back-end side, this is possible just by adding numeric 4. Technically, square 4+4 is square 8.
Suppose, the token is on square 97. When the dice displays the number greater than 3, the token remains still on same location unless the displayed number is less or equal to 3 preventing player to win the game.
