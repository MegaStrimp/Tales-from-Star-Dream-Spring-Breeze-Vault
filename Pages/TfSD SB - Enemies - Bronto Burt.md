## Bronto Burt
![[TfSD SB - Image - Enemies - Bronto Burt.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 100

A spherical creature with insect-like wings that flies through the air.  
Referred to in-game as 'Bront Burt'.
### AI States
#### Up and Down
The enemy flies up and down in a wave-like behavior.
#### Bounce Fly
The enemy flies by doing timed jumps in midair.
#### Circle Chase
The enemy flies straight downward while following the player's direction, does a circular move once it's y position reaches one tile under the player, and flies straight horizontally when the circle is done.
#### Hop and Fly
The enemy does a slow jump and starts flying straight horizontally as it falls halfway through a tile.
#### Up and Down Hard
The enemy flies up and down without friction.
#### Fly Straight Horizontal
The enemy flies straight horizontally to the player's direction.
#### Up and Down Hard Long
The enemy flies up and down without friction with a longer period.
#### Circle Chase Close
Same as [[TfSD SB - Enemies - Bronto Burt#Circle Chase|Circle Chase]] but the enemy can't change direction, and activates when the player exceeds their x position to the direction the enemy is facing.
#### Circle Chase Double
The enemy activates when the player exceeds their x position to the direction the enemy is facing, moves downward while following the player's direction, does a double circular move once it's y position reaches one tile under the player, and flies straight horizontally when the circle is done.