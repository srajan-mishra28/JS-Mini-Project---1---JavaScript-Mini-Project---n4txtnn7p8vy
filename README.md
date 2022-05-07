# Classic Rock Paper Scissors Game which you can play with cpu

This is a Rock Paper scissors game, which has been made using HTML, CSS ans javascript. The webpage has been designed with HTML and CSS and the functionality has been added with Javascript. app.js contains these functions:

main() - When an user click on rock, paper or scissors, this function takes that input and passes it to the game() method.

getCPUchoice() - This function generates CPU choice. Floor value of Math.random() function multiplied by 3 gives us a random number among these numbers -[0,1,2], which has been used to decide CPU choice.

game() - This function checks the result of the game and according to that, it calls win(), lose() or draw() function.

win() - This function updates user score and the display message.

lose() - This function updates CPU score and the display message.

draw() - This function onl updates display message.
