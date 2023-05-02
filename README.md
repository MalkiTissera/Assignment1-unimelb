
# Python Board Game

## Rules of the Game
This is a single player game. The game loads data from a .csv file which contains educational questions about programming. The game generates a random goal from a fixed list of rooms which the player needs to find. There are two modes to the game: NORMAL mode with the goal known and HARD mode with the goal unknown. The player also selects what piece they want to use on the map to represent themselves: X, O, or P.
For each turn, the player needs to choose to either move to the right or move down. The first room visited is always the same regardless of the move. A challenge question is presented for every room visited. A player wins if they reach the goal while answering all questions correctly along the way. The game is over when: when a player does not answer a question correctly, or when a player does not reach the goal and ran out of rooms to visit. It is not possible to move back to a room. Therefore, if the player misses the goal and reaches the last room, it will be game over even though the player successfully answered all the challenge questions in the rooms they visited.

Example output from the game where the goal is to go to the game room, player is currently in dining:

Location is dining

[ P ][ living ][ garden ]</br>
[ lounge ][ game ][ gym ]</br>
[ spa ][ bedroom ][ office ]

## Files
questions.csv: The data file containing questions that should be answered by the player in the game.

template_application.ipynb: The Jupyter Notebook containing the code for the game.

README.md: This file, providing an overview of the project and instructions for usage.
