# 10C Final Project: Voltorb Flip

The eventual goal of this project will be to have a fully-functioning version of the Pok�mon minigame Voltorb Flip. It is a Minesweeper-esque game where the player flips over face-down cards that are either labeled with numbers or exploding mines ("Voltorbs"). The gameplay involves progressing through levels while amassing as many coins as possible. Within a level, flipping over a number will give the player that many coins to start with, while subsequent numbers multiply the coin total. If the player flips over all numbers, they win and advance to the next level. The mines force a Game Over and take away all coins gained in that round, while resetting the player's level.

https://bulbapedia.bulbagarden.net/wiki/Voltorb_Flip

I plan to begin writing this project with Visual Studio with standard C++ code. It will rely on console inputs and outputs, and will have to print the gamestate and gameboard after every input. It will not be able to support things such as flagging positions (like in Minesweeper, placing a flag over a spot to indicate possible mines, or a possible number, which is unique to this game) because a text-generated game board will not be able to display that sort of information in a neat way. Once I have a functional game, I will attempt to port the project into Qt. I will add that functionality as well as other possible bonuses, such as additional casino minigames that the series has been known for.