# TicTacToeGame
TicTacToe project for wdi
This is a fairly simple game I created for WDI class.

My initial plan for the game was to use canvas elements for the board, but it became very difficult implementing the funtionality
I wanted for the game with this method, my initial plan  was to get all the basics done with a set of 2 variables; one
for the players another for the board. THen a set of four to six functions that would determine if X or O have won by parsing through
the board with for loops. 

Initially I wanted to set player names using alert prompts, I could not get this feature to work,
so I simply set an editible text input field where users could type their names. This field does not refresh when
the new game button is hit.
After some frustration I restarted the entire program using a very brute force method that would rely on
input buttons on the html page; when clicked each button would first display X first then O. Then cycle through all possible
entries for X or O on the game board with a series of && || statements that would declare a winner based on
every possible winning out come for having three consecutive X or O values horizontally, vertically, or diagnally.

In reality only 1 player is coded
into the game, the x's and o's turns are based on the player variable set to 1, after the first x is placed the first
part of the statement becomes 0 or false, allows o inputs to be placed. After an O has been placed =+ 1 is added to the 
if else statement and sets the value back to the 1/True/X input.
When a player wins, the reset is initialized which clears the board. 
The new game button isnt really neccessary. And tends to lead to misclicks where games are accidently restarted.

If I were to try this again, I would definatly consider adding loops to iterate over the board to determine winners instead
of brute forcing my way through it.
I would also implement the set player name in a better way, aswell as implement the ability to track scores.

![Imgur](http://i.imgur.com/4iIHsnB.jpg)

