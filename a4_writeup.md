# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
The most difficult part to tic-tac-toe was ensuring that the has_won method accounts for all scenarios in which you can win in tic-tac-toe, as in not just making the vertical scenario only count as a win, but also including a horizontal scenario and diagonal.

2. Explain how you would add a computer player to the game.
You could add a computer player to the game by creating a randomizer that chooses a number from 0-8 and placing a circle or x depending what you decide the computer player be and checking whether that number's space is open. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
If I add a computer player, I might get the computer to play the best move every time by first programming it to always choose one of the corners of the board, whichever closest one to zero that is open. Then I will make it attempt to place another one to two more of the corners if they are open and connecting one fo the corners to the other if open. If none of these are open, then the optimal method of the computer would just to place one next to a previous circle/x to the corner and connecting the final one accordingly if the space is open.