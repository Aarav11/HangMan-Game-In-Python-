
This Project is created in Python and its a project or a game of Hangman 

# About Hangman
Going back to our old school days, some of the pen-paper games were always a top for our leisure time. Hangman was one, other than some chit games, to guess words according to the guesses determined and as soon as they lost all their wrong guesses, they were hanged (not really, but on paper 😉 ). That is an old way, now to play Hangman. The new advancement in technologies allows us to play hangman using our own computer also without any other player. How? Let’s find out further

# Project Prerequisites

This project requires good knowledge of Python which includes defining functions and managing for/while loops. The functions that we use here contain arguments that are defined in a global scope which can be further used in other functions to improve game quality. It can also be used to provide different steps when required to execute upon conditions by the for and while loops.

# Project Steps
Importing the random and time modules.

Defining functions with specific global arguments.

Implementing loops to execute the program.

Passing the function in the program to run.

# Code Explanation

If the letter is correctly guessed, index searches for that letter in the word.

Display adds that letter in the given space according to its index or where it belongs in the given word.

If we have already guessed the correct letter before and we guess it again, It tells the user to try again and does not lessen any chances.

If the user guessed the wrong letter, the hangman starts to appear which also tells us how many guesses are left. Count was initialized to zero and so with every wrong guess its value increases with one.

Limit is set to 5 and so (limit- count) is the guesses left for the user with every wrong input. If it reaches the limit, the game ends, showing the right guesses
(if any) and the word that was supposed to be guessed.

If the word is guessed correctly, matching the length of the display argument, the user has won the game.

Play_loop asks the user to play the game again or exit.

Main() and hangman() would start again if the play_loop executes to yes.

# Summary

A Advanced or Basic Python Hangman Game 
