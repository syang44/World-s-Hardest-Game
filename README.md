# World-s-Hardest-Game
My partner and I created a game inspired by the World's Hardest Game for our final project in ECE243. It is developed in C for the ARM processor and is intended to operate on a DE1-SoC board. It can also be run on the [CPUlator simulator](https://cpulator.01xz.net/?sys=arm-de1soc). I cannot distribute the code here due to academic integrity but I would be happy to share the code to individuals that are interested.

# Instructions
After compiling, you will see the initial homescreen. To proceed, press the 'enter' key to continue. On CPUlator, type in the PS/2 keyboard simulator.

![alt text](https://github.com/syang44/World-s-Hardest-Game/blob/main/Demo/Control.png)

The goal is to move the red square using the arrow keys from one green area to the other without hitting the blue squares. (You would still be typing in the PS/2 keyboard simulator if using CPUlator).

![alt text](https://github.com/syang44/World-s-Hardest-Game/blob/main/Demo/Level%201.png)

If the map has coins (orange boxes), the player must collect all the coins in order to beat the level.

![alt text](https://github.com/syang44/World-s-Hardest-Game/blob/main/Demo/Level%202.png)

There are a total of 6 levels, each with different enemy movement patterns and map layouts. You can use the KEY pushbuttons to select a different level.

![alt text](https://github.com/syang44/World-s-Hardest-Game/blob/main/Demo/KEY%20pushbuttons.png)

After you win, press 'Esc' key to return to initial screen.

![alt text](https://github.com/syang44/World-s-Hardest-Game/blob/main/Demo/Win%20screen.png)

Additional features include messages on the HEX display (when you lose, win, etc.), and audio when you collide with the enemy.

See Demo folder for videos of game.
