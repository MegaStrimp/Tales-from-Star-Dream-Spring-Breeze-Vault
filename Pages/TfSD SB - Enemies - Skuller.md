## Skuller
![[TfSD SB - Image - Enemies - Skuller.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 1000

A skull that flies after the player and cannot be inhaled.

It is the [[TfSD SB - Gamemodes - Extra Game|Extra Game]] version of [[TfSD SB - Enemies - Mumbies|Mumbies]].
### AI States
#### Down and Turn
The enemy flies downwards, and turns left and right in a wave-like behavior. It's y direction changes with a timer.
#### Up and Turn
The enemy flies upwards, and turns left and right in a wave-like behavior. It's y direction changes with a timer.
#### Follow Player
The enemy follows the player horizontally, and vertically only if the player's y position is more than one tile away from the enemy. The following move activates and stops with a timer. When the move activates, the enemy changes it's sprite direction based on the player.
#### Rotate
The enemy rotates in a pre-determined center with the radius changing in a wave-like pattern and with a timer. They change their sprite direction based on their position in the circle.
#### Up and Down
The enemy flies up and down in a wave-like behavior.