# Find Mortimer the mouse by guessing a number between 1 and 20.
## The objective of the game is to pick a number between 1 and 20, each guess will lower the initial score of 20 by 1 and will either tell you the number is too high, too low or invalid. The game stops when you guess the correct number or when the score reaches zero.
The purpose of this is to showcase JavaScript fundamentals such as objects, methods, logical operators, functions etc while also showcasing DOM manipulation. I used document.query selector to select and alter elements such as "score", "message", "number", "check", "guess" etc to make the game interactive with the users input. For the game logic I used the Math operator alongside the .random method to pick a random number between 0 and 0.9999 and the .trunc method to discard the numbers after the decimal point once we multiplied the value by 20 to get a number between 0 and 19, I then simply added 1 to generate a number between 1 and 20. I then used a series of if and else if statements alongside document.queryselector to manipulate the values on the HTML and CSS files.

## As the purpose of this was to showcase JavaScipt fundamentals and basic DOM manipulation the game is not responsive. Its was built to work in a 1920 * 1080 so may not work look good on a smaller screen.
