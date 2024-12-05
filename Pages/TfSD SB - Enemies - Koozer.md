## Koozer
![[TfSD SB - Image - Enemies - Koozer.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 400

A black, spherical creature that flies in erratic patterns, often following the player.

It is the [[TfSD SB - Gamemodes - Extra Game|Extra Game]] version of [[TfSD SB - Enemies - Bronto Burt|Bronto Burt]]
### AI States
#### Up and Down
The enemy flies up and down in a wave-like behavior.
#### Bounce Fly
The enemy flies by doing timed jumps in midair. Jump direction is based on the player's position.
#### Up and Down Hard
The enemy flies up and down without friction.
#### Fly Straight Horizontal
The enemy flies straight horizontally to the player's direction.
#### Up and Down Hard Long
The enemy flies up and down without friction with a longer period.
#### Chase
The enemy flies straight downward while following the player's direction and once it's y position reaches one tile under the player, it instead starts flying straight horizontally.
#### Chase Close
Same as [[TfSD SB - Enemies - Koozer#Chase|Chase]] but the enemy can't change direction, and activates when the player exceeds their x position to the direction the enemy is facing.
#### Hop and Fly
The enemy does a jump and starts flying straight horizontally when it goes up 1 tile.
#### Fly Straight Horizontal Fast
The enemy flies straight horizontally with a fast, accelerating speed.
#### Circle Chase Close
The enemy does a circular move once the player exceeds it's x position, and flies straight horizontally when the circle is done.