## Scarfy
![[TfSD SB - Image - Enemies - Scarfy.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 800

Floats up and down in the air. If the player attempts to inhale it, the enemy switches to [[TfSD SB - Enemies - Scarfy#Appear Close|Angry]]. Explodes on death.
### AI States
#### Appear Close
The enemy appears when the player's x position is 3.5 tiles close to them, dashes to their own y direction, and then flies up and down in a wave-like behavior.
#### Angry
The enemy chases the player that has triggered their state, and explodes after a few seconds.
#### Up and Down
The enemy flies up and down in a wave-like behavior.