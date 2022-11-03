# Jeopardy Clone Trivia Game
Using the "jService" api I made a working Jeopardy board. By clicking 'Start Game' at the bottom, six random categories are displayed. A correct answer will update your score at the top.

**Link to project:** https://jeopardy-type-game.netlify.app/

![triviaGame](https://user-images.githubusercontent.com/103867568/199621453-5c4c2e70-e3fe-4ef9-b67d-bbff1a134b3e.jpg)

## How It's Made:

**Tech used:** Javascript, CSS, HTML

While making this project, I really wanted to focus on having Javascript do the heavy lifting. Instead of hard coding the repeatative grid of boxes I only had to code a couple of sections and used dom manipulation to do the rest. This makes the board more dynamic and easy to resize and reshape in possible future projects. Then it was fairly straight forward writing a function to go through and use a fetch to call the api and use that data to fill the boxes. When first making the boxes I added event listeners to them so when clicked on they will display the proper question in the form of an alert, give you a chance to answer, and then to nigate any discrepencies that could come up you're given the chance to challenge the ruling if you disagree with the game logic. 
