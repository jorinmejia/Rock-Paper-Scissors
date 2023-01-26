# Rock-Paper-Scissors
A simple rock, paper, scissors game in Python

Design:
I decided to create this simple rock paper and scissors game using a while loop. The idea is to place the options of "rock", "paper", and "scissors" in a list and the computer will randomly chose an option. The user of the program will type their option as well and using if, elif statements, it will compare the user and computer options. This program will continue to track the score of either the user and computer until the user decides to quit the program. 

Implementation:
1. First, I created two variables that will keep count of the times the user and computer have won.
2. Created a list that contains "rock", "paper", "scissors" and named the list options. This will be useful in order for the computer to randomly chose an option.
3. Using a while true loop, this program will continue until the user decides to quit the game.
4. Then ask the user to input either rock, paper, or scissors as their choice. If user chooses differently then it will ask the user to enter a correct option.
5. The computer will choose a random choice from the options list.
6. Using if, elif statements, we compare both the user and computer options and decide a winner.
7. Add 1 to either the user score or computer score depending on who won.
8. Game restarts but will contain the current score until user decides to quit. 

Test: Works great. 