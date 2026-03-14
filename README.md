sidequest_W6

Ellis Byun, esbyun, 21079246

Description: 
The player plays as a fox in a forest environment, tasked with rescuing leaves scattered across various platforms. The player must jump across platforms, 
avoid fire, and evade or hit boar enemies. Each time the fox is hurt by fire or a boar, it loses a life (out of three total). The game tracks rescued 
leaves (goal: 15) and remaining lives, and has an internal timer to measure completion speed. When the player dies or succeeds, the timer freezes, providing 
performance feedback.

Setup and Interaction Instructions: 
- Load game in a web browser
- Press any key or click the screen to begin
- Arrow keys (left, right, up) or A, W, D keys to move
- Up arrow key or W key to jump
- Space bar to hit enemies (boars)
- Collect all 15 leaves as quickly as possible
- Avoid taking damage from fire and boars (each hit costs 1/3 lives)
- Rescue all leaves to win

Changes Made:
- Integrated sound effects with gameplay actions:
Leaf collection -> leafCollect.wav
Player taking damage -> receiveDamage.wav
Enemy hit -> hitEnemy.wav
Jump -> jump.wav
- Made BGM (music.wav) play when audio is triggered and looped BGM

Assets:
All audio assets sourced from Week6_Example05 > assets > sfx:
- hitEnemy.wav - boar (enemy) hit sound
- jump.wav - player jump sound
- music.wav - background music
- receiveDamage.wav - player hurt sound
- leafCollect.wav - leaf collection sound

References:
Cochrane, K., & Han, D. (n.d.). GBDA 302 Week 6.
https://learn.uwaterloo.ca/d2l/le/content/1221157/Home?itemIdentifier=D2L.LE.Content.ContentObject.ModuleCO-6357798 
