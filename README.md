# Teeko Bot
 
Teeko is a game between two players on a 5x5 board. Each player has four markers of either red or black. Beginning with black, they take turns placing markers (the "drop phase") until all markers are on the board, with the goal of getting four in a row horizontally, vertically, or diagonally, or in a 2x2 box as shown above.

If after the drop phase neither player has won, they continue taking turns moving one marker at a time -- to an adjacent space only! (Note this includes diagonals, not just left, right, up, and down one space.) -- until one player wins.

This game is a modified version of the same:
The Teeko2 rules are almost identical to those of Teeko but we will exchange a rule. Specifically, we remove the 2x2 box winning condition and replace it with a diamond winning condition. Any diamond is defined by an empty center position surrounded by 4 markers on the spaces above, below, to the right, and to the left of the center. 

I have developed an AI game player using the minimax algorithm which makes its move in under 5 seconds and beats a random player in about 95% of the matches.

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/Teeko_board.jpg" alt="teeko board" width="250" height="250">
