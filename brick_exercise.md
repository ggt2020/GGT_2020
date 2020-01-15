# Brick Exercise

It is now time to apply the concepts you have learnt and let's build a game! Please complete the exercise in the Brick_GGT_worksheet.py in order to run the game.

## Exercise 1
Write a function named 'hit_wall_top' in class Ball to implement the logics when the ball hits the top of the game area. <br>    
Arguments: <br>
&nbsp;&nbsp;&nbsp;&nbsp;game: the game object <br>
Return: <br>
&nbsp;&nbsp;&nbsp;&nbsp;True: if the ball hits the top of the game area <br>
&nbsp;&nbsp;&nbsp;&nbsp;False: if the ball does not hit the top of the game area <br>

(Don't forget to uncomment the code that calls the function.)

## Exercise 2
Modify the function create_bricks to create random number of bricks in a row. Right now it is always 5. <br> 
Make sure the number is between 1 and 8. <br>
(Don't forget to import the library.) <br>

## Exercise 3
(A bit challenging but is nice to have. You can complete the other exercise first and come back to it.) <br>
Extend or add new gestures to pause and resume the game. Also implement the functions when the gestures are performed. <br><br>

Hint: Game state can be 'Off' and 'Running' right now. Come up with a new state when the game is paused. <br> <br>

TODO: <br>
Write a function named pause_game. Save the current ball speed and update the speed.<br><br>

Write a function named resume_game. Update the ball speed to the speed before pause.<br><br>

When pause key is pressed, check if the game state is running. If so, pause the game.<br><br>

When resumne key is pressed, check if the game state is paused. If so, resume the game.<br>

## Exercise 4
Update the title of the game and make it yours!

## Exercise 5
The racket is moving a bit too slow right now. Adjust the speed of the racket to make the game more user-friendly.

## Other Features 
* Game state update and message upon completion
* Colors of the brick
* Scoring
* Music and sound effects
* Anything you can think of
