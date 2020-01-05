# WebDevCourse
Gen10


LUCKY SEVENS GAME:

In this assessment, you will demonstrate all you have learned in the HTML, CSS, and JavaScript modules by writing a program that plays Lucky Sevens. The rules of the game are as follows:

As long as there is money, play the game.
Each round, the program rolls a virtual pair of dice for the user.
If the sum of the 2 dice is equal to 7, the player wins $4
Otherwise, the player loses $1.
Your job is to write a program that plays this game, which will also demonstrate the futility of playing Lucky Sevens.


Requirements
The game should be laid out like this:
Lucky Sevens Starting Screen - Laid out in three lines:
1st line- Lucky Sevens header
2nd line - A label with 'Starting Bet' and a textbox that accepts a money value
        3rd line - A button labeled 'Play'
Initial game layout
The program asks the user how many dollars they have to bet.
If the starting bet is less than or equal to 0, display an error message.
When the user clicks the Play button, the program then rolls the dice repeatedly until all the money is gone.
Hint: Use a loop construct to keep playing until the money is gone.
Hint: We created a rollDice() function in the Rolling Dice exercise.
The program keeps track of how many rolls were taken before the money ran out.
The program keeps track of the maximum amount of money held by the player.
The program keeps track of how many rolls were taken at the point when the user held the most money.
Hint: For steps 4, 5, and 6, declare some variables.
When the game is over, display the following output:
lResults screen layout - 6 rows of layout:
1st row - Lucky Sevens header
2nd row - 'Starting Bet' label and textbox for starting bet
3rd row - 'Play' button has its label changed to 'Play Again'
4th row - horizontal rule
5th row - Results header
6th row - Table of results

The table of results includes:
- Starting bet label and amount
- Total rolls before going broke label and amount
- Highest amount won label and amount
- Roll count at highest amount won label and amount
Sample output at end of game


RESTAURANT SITE:

In this assessment, you will revisit the restaurant site that you created in the CSS Restaurant Site 2 code assessment. You will apply what you have learned about JavaScript in general and its plugins in Bootstrap.

Requirements:
Add Bootstrap to the site.
Style the site navigation so that you are using either tabs or pills.
Use a jumbotron or page header to call out big news - your restaurant is opening a new location!
Make the site responsive using Bootstrap's grid system.
The menu items should stack well, with no overlapping.
The front page content should stack as well.
Change the Home link to use an Icon from one of the supported fonts that looks like a house.
Add a Carousel that rotates with three pieces of information:
We're opening a new location!
We're rolling out our seasonal menu, with special options for this season.
The Drink of the Month is SG Special Brew.
Use the Bootstrap form items for your Contact Us form, validate in Javascript that data has been provided and give a message that the information is valid without submitting it anywhere.
Make sure that users who have JavaScript disabled know that this site is best viewed with JavaScript enabled.
