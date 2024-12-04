## Mumbies
![[TfSD SB - Image - Enemies - Mumbies.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 1000

Spherical, mummy-like enemies that slowly fly around and cannot be inhaled.
### AI States
#### Down and Turn
The enemy flies downwards, and turns left and right periodically. The turning move activates and stops with a timer. Every third turn, the enemy's sprite changes direction.
#### Up and Turn
The enemy flies upwards, and turns left and right periodically. The turning move activates and stops with a timer. Every third turn, the enemy's sprite changes direction.
#### Follow Player
The enemy follows the player horizontally, and vertically only if the player's y position is more than one tile away from the enemy. The following move activates and stops with a timer. When the move activates, the enemy changes it's sprite direction based on the player.
#### Rotate
The enemy rotates in a pre-determined center with the radius changing in a wave-like pattern. They change their sprite direction based on their position in the circle.
#### Up and Down
The enemy flies up and down in a wave-like behavior.