# Python Guessing Game:

![Guessing_Game pictures](Import.png)

Using the random number generator, user input and a nested loop to create a simple guessing game using python. 

First I imported random, which is buildt into python, to allow you to generate random numbers.

Second through the use of the randint function. I created the variable used this function to generate a random number valuing between 1 and 10. 

![Guessing_Game pictures](While Loop.png)
Third I used a while loop with a nested if loop. When the while loop is True, the user is asked to guess a number 1 through 10. 
 - user input is taken from the guess variable and formated to ensure the the input is an integer. 
 -If: the user guesses to low, the program prints "Too Low"
 -elIf: the user guesses to  high, the code prints "Too High"
 -else: code prints "You Won"
 
 ![Guessing_Game pictures](Play Again.png)
 
Lastly the nested if loop allows the user the option to play again.
-creating a third variable name play_again: the user is aked to input y or n
-if: y is enter the game starts again
-else: the code prints "Thank you for playing" and exits out of the while loop

