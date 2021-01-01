# Python Guessing Game:
<p align="center">
 <img src="/Guessing_Game_Pictures/Import.png" alt="Import">
</p>

Using the random number generator, user input and a nested loop to create a simple guessing game using python. 

First I imported random, which is built into python, to allow you to generate random numbers.

Second through the use of the randint function. I created the variable used this function to generate a random number valuing between 1 and 10. 

<p align="center">
 <img src="/Guessing_Game_Pictures/While_Loop.png" alt="While_Loop">
</p>

Third I used a while loop with a nested if loop. When the while loop is True, the user is asked to guess a number 1 through 10. User input is taken from the guess variable and formated to ensure the the input is an integer. 
 -If: the user guesses to low, the program prints "Too Low"
 -elIf: the user guesses to  high, the code prints "Too High"
 -else: code prints "You Won"
 
<p align="center">
 <img src="/Guessing_Game_Pictures/Play_Again.png" alt="Play_Again">
</p> 
 
Lastly the nested if loop allows the user the option to play again.
-creating a third variable name play_again: the user is aked to input y or n
-if: y is enter the game starts again
-else: the code prints "Thank you for playing" and exits out of the while loop
