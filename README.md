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
* The game space is too small and compact.
* The duration of the POV mode is static, and the player can not extend it somehow.
* Jumping is awesome, however, jumping over the bumpers is not a good idea.
* There is no jumping sign to say jump over this wall to go to the next level or so.
* It would be better to know the duration of POV mode before entering into it.

## Playtest #3 - beta test
For the last playtest, which I have arranged myself, I remodel the whole board in blender and made it larger and more amusing. In addition, I repositioned the bumpers to make the game more fun. Then, I got rid of mouse as a controller and replaced it with arrows, so player will have a comfortable hand position to play the game. Added various elemets to UI such as Controls, the Goal of the game, "next level unlocks at: X points", and the duration of POV mode. I have made a connection between Multiplier's value, duration of POV mode, and the thereshold in which POV mode becomes available; so as the multiplier's value goes higher than the threshold, and player have not yet used its super power, an specific amount will be added to the POV mode duration based on the difference between the multiplier and the threshold. At this point, if player goes to POV mode, s/he has more time to spend in POV mode, nonetheless s/he also has set the threshold to a higher level which makes the game a bit harder. To solve the "jumping over the bumpers" issue, I added a glass top, which is open on both ends for level transitions, on top of the boards. Afterwards, I added a jump sign at the end of the board which apears in POV mode whenever the next level is unlocked.

After these adjustments and changes, I arranged a playtest session with couple of friends and family, and here is its outcome:
* With this board layout, it is a bit easy to lose. The ball goes on the sides often and falls into the hole.
* Jumping acts a bit weird and player can only jump once.
* It is really hard to jump and control the ball at the same time, and it is even harder to land the ball to the next level properly.
* When player jumps from one board to another, most of the times it land on the top glass part which is literally outside of the game.

## The Final Game
For the final game, two main issues that I had to fix was 1) players lose easily because of the game layout , and 2) everything related to jumping in POV mode. I have found out that the problem with jumping was related to the baumciness of the board, whish made the ball baunce back and forth the whole time, so it was hard press jump button exactly at the point that the ball is grounded. I tried to fix it in many different ways, however I could not get what I desired; so I decided to get rid of the jump completely and add a ramp instead, which works pretty awesome. To solve the landing on the top glass issue, I basically remodel the top glass and made it a way to lead the ball in to the playground.
For the other issue, I solved it by adding two extra bumpers at the bottom of the board on both sides of the hole, which I think made the game even more interesting.
At the end, for the final touch, I added a HIGH SCORE system along some sound effect to make the game almost compelete.

Thank you for playing my DOPE pinball

ENJOY

EBBY
