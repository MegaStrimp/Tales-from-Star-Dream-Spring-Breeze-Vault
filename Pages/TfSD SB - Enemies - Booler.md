## Booler
![[TfSD SB - Image - Enemies - Booler.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 400

This ghost floats in circles or jumps around.
### AI States
#### Fly Straight Horizontal
The enemy walks on a straight line and changes direction when it touches a wall. Room boundaries and gravity don't effect them.
#### Jump and Float
The enemy jumps, floats in a curve, lands back to the opposite side, the does another curve to land back to their spawn.
#### Circle
The enemy waits a little bit, does a circular move, and flies straight to where they're facing when the circle is done.
#### Up and Down
The enemy flies up and down in a wave-like behavior.
#### Rotate
The enemy rotates in a pre-determined center with the radius changing in a wave-like pattern. They change their sprite direction based on their position in the circle.
#### Jump and Squish
The enemy falls down, squishes when grounded, and jumps back after a few frames. Turns around after a few seconds, at the peak of their jump.
#### Boomerang
The enemy dashes forward and upwards, changes it's direction to slowly fly backwards and downwards, then does another dash to the direction they're currently facing.