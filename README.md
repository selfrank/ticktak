# ticktak
Ticktak game to practice passing state between parent and child

About:
Using ticktaktoe this project practices passing state between child and parent in react. The code uses board as the parent and box as the child. You can see the call back functions that pass the state back and forth between the parent and the child components. 

Improvements:
1. I want to improve the styling of the boxes. The colors are hard to look at. I would update the CSS to use some friendlier color schemes. Coding in red and green is not accessible to those with color blindness.

2. I want to add an option for player one and player two to enter their names.

I would add an input box and use 1, or 0 is used to identify x or o to display their names instead of player x, player 0.

3. I want to add an alert when someone has won with a button to refresh the page and start the game over. 

I will add an alert trigger in the checkForWinner function and add a button with onClick={refreshPage}. 
