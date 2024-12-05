## Grumples
![[TfSD SB - Image - Enemies - Grumples.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]
**Points -** 400

A stone head that jumps, glides or floats while spinning. When in the air, it teleports around and chases after the player if they gets near.

It is the [[TfSD SB - Gamemodes - Extra Game|Extra Game]] version of [[TfSD SB - Enemies - Kabu|Kabu]].
### AI States
#### Walk and Turn
The enemy walks back and forth in a wave-like behavior.
#### Jump and Turn
The enemy jumps upwards with horizontal movement, and turns around when they touch ground. The jump has a timer.
#### Idle
The enemy stands still with their movement animation. When the player gets underneath the enemy, it switches to [[TfSD SB - Enemies - Grumples#Chase|Chase]].
#### Idle Fast
The enemy stands still with their movement animation, played in a faster pace.
#### Chase
The enemy rises above with their movement animation playing, and after a few frames, it starts chasing the player.
#### Invis
The enemy floats up and down in a wave-like behavior, and turns invisible for a few seconds with a timer. It does a short flash before disappearing and reappearing. The enemy also starts a few pixels above. When it reappears, the enemy switches to [[TfSD SB - Enemies - Grumples#Chase|Chase]].