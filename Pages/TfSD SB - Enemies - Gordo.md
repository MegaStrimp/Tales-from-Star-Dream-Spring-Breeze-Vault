## Gordo
![[TfSD SB - Image - Enemies - Gordo.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]

An invincible, spiked ball that travels on a set path. Deals three bars of damage. Their animation speed changes from normal to fast with a timer.
### AI States
#### Horizontal
The enemy flies left and right in a wave-like behavior. The animation speed changes based on the movement.
#### Vertical
The enemy flies up and down in a wave-like behavior. The animation speed changes based on the movement.
#### Zig Zag
The enemy follows a zig zag path based on it's movement.
#### Door
The enemy flies up and down for half a tile without friction. Deals equal damage to the player's max health.
#### Vertical Stop
The enemy flies up and down with a timer and stops for a few frames before turning around. Both directions have different stopping times. It also goes left and right in a wave-like behavior. The 
animation speed and wave speed increases while it's stopped.
#### Horizontal Jump
The enemy flies to the direction it's facing and jumps back after a timer. The animation speed gets faster while it's close to jumping.
#### Vertical Fast
The enemy flies up and down faster in a wave-like behavior. The animation speed changes based on the movement.
#### Horizontal Hard
The enemy flies left and right with a timer.
#### Vertical Hard
The enemy flies up and down with a timer.
#### Fall
The enemy falls down while moving horizontally to it's direction. Room boundaries and gravity don't effect them.
#### Fall Fast
The enemy falls down while moving horizontally to it's direction in a faster speed. Room boundaries and gravity don't effect them.
#### Follow
The enemy flies left and right with a timer and after going back, it flies one tile vertically depending on the player's position.