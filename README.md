# Jeopardy Clone Trivia Game
Using the "jService" API I made a working Jeopardy board. Six random categories are displayed by clicking 'Start Game' at the bottom. A correct answer will update your score at the top.

**Link to project:** https://jeopardy-type-game.netlify.app/

![triviaGame](https://user-images.githubusercontent.com/103867568/199621453-5c4c2e70-e3fe-4ef9-b67d-bbff1a134b3e.jpg)

## How It's Made:

**Tech used:** Javascript, CSS, HTML

While making this project, I wanted to focus on having Javascript do the heavy lifting. Instead of hard coding the repetitive grid of boxes I only had to code a couple of sections and used dom-manipulation to do the rest. This makes the board more dynamic and easy to resize and reshape in possible future projects. Then it was fairly straightforward to write a function to go through and use a fetch to call the API and use that data to fill the boxes. When first making the boxes I added event listeners to them so when clicked on they will display the proper question in the form of an alert, give you a chance to answer, and then negate any discrepancies that could come up you're given the chance to challenge the ruling if you disagree with the game logic. 

## Lessons Learned:

I took away how useful it can be not directly writing your javascript and the template it can give you for later projects. Also after completing this project I feel more comfortable working with promises and API's overall. 
