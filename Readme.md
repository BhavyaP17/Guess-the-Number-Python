"""
"Guess the Number Python"
-------------------------
import the random module from python's inbuilt libraries

user inputs a number; a lower limit and an upper limit.

After getting the upper limit and the lower limit within which a random number will be selected, we pick a random number using a function from the random module.

The user is then assigned a number of chances to guess a number which will be a counter for a loop. We use a while loop since the user can get the right guess at any trial. The while case will check if the user has guessed the right number and if so, exits the loop. If not the number of chances decrements by one until the user has no more chances and the random number is revealed to him.

To ensure that the program runs continuously and doesn't close the program window, we add a true statement and print a line to separate the blocks.



"""