# DOPE pinball Journal
## Playtest #1 - prototyping a new mechanic
My initial idea for a new mechanic was the fact that I wanted to create a new experience in pinball; a sort of experience which one can not acheive in playing arcade version of PinBall and it is only possible digitally; that was the moment when the idea of having POV camera on the ball and controlling it came into my mind.
For the first playtest, I started from the basic pinball that we made in the class and added the second camera and a script to control the ball. Basically, when the "multiplier" reaches a threahold, player could press SPACE to enter the POV mode and controls the ball for a limited time. Then camera would return to its initial position and the player could not control the ball anymore.

Based on the playtesters' feedbacks, here are some aspects of my game which needed to work on:
* Too many controls (ctrl, shift, alt, w, a, s, d, mouse) makes the game too difficult to play.
* The ability of rotating the camera in POV mode is too much and confusing.
* Player doesn't know how much time s/he has in POV mode and it jumps out of it suddenly.
* Bumpers are too big compared to the board.
* Nothing is in the UI to help players understand what to do and how to play the game.
* Nothing indicats that the player is able to use its "SUPER POWER", or at what point in the game SUPER POWER is available.
* It is not clear what is the objective of entering POV mode.
* If player looses on POV mode, when the game resets, it is still in POV mode.

## Playtest #2 - alpha test
As I have planed since the beginning, I wanted the player to be able to jump to the next level in POV mode, and by jumping I mean literally jump from the current pinball set to another. I fixed camera rotation in POV mode so it does not confuse the player. Then reduced the controls W,A,S,D,SPACE,and 3 mouse buttons. The jumping abilitiy during POV mode was added along another pinball set to jump to. I also solved the reseting issue by reloading the scene compeletly. For UI, I added a text indicating when SUPER POWER would be available (based on the Multiplier's value), and I made its treshshold increase each time the player enters to POV mode. Furthermore, I made a text saying "press SPACE use super power" appear whenever player's multiplier reaches the threshold. At last, I added a timer (countdown) to show the player how long its super power will last. Unfortunately, I could not manage to add the controls in UI.

With all these changes, here are some points from playtesters' feedbacks:
* There is nothing to show how to play the game in UI.
* Walls need some work, as well as bumpers.
* The duration of the POV mode is static, and the player can not extend it somehow.
* Jumping is awesome, however, jumping over the bumpers is not a good idea.
* There is no jumping sign to say jump over this wall to go to the next level or so.
* 

## Playtest #3 - beta test


## The Final Game
