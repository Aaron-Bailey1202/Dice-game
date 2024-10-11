# Dice-game
This is a simple web application that simulates a dice game between two players, with the result displayed on the page. The app is built using HTML, CSS (through a linked stylesheet), and JavaScript to handle the logic of the game.

Dice Game
Overview
This project is a simple web-based dice game where two players "roll" dice, and the result is displayed directly on the page. The game generates two random dice rolls and announces a winner based on the higher roll. If both players roll the same number, it results in a draw.

Features
Simulates rolling dice for two players.
Dynamically updates the images of the dice based on random values.
Displays the result ("Player 1 Wins!", "Player 2 Wins!", or "It's a draw!") on the webpage.
Refresh the page to re-roll the dice.
Technologies Used
HTML: Defines the structure of the page.
CSS: (via a linked stylesheet) for basic styling.
JavaScript: Handles the logic of generating random dice rolls and updating the page.
How It Works
When the page is loaded or refreshed, the index.js script runs.
Two random numbers between 1 and 6 are generated, simulating the roll of two dice.
The images of the dice are updated based on the random numbers generated.
The result is displayed in the <h1> element:
If Player 1 rolls a higher number, "Player 1 Wins!" is displayed.
If Player 2 rolls a higher number, "Player 2 Wins!" is displayed.
If both rolls are equal, the result is a draw.

How to Run
1) Clone or download this repository to your local machine.
2) Make sure all dice images (dice1.png to dice6.png) are in the /images folder.
3) Open index.html in any modern web browser.
4) Refresh the page to play the game, and see which player wins!
