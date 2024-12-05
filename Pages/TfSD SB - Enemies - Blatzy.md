## Blatzy
![[TfSD SB - Image - Enemies - Blatzy.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]

An indestructible, immobile cannon that fires cannonballs at the player very rapidly.

It is the [[TfSD SB - Gamemodes - Extra Game|Extra Game]] version of [[TfSD SB - Enemies - Shotzo|Shotzo]]
### AI States
#### Shoot Straight
The enemy shoots straight to their direction after a few frames of reload time.
#### Bounce and Attack
The enemy bounces a tile above and does a five-way attack. Both actions are asynchronous.
#### Follow Player
The enemy's aim follows the player in 5 directions and when it's locked in, they shoot to that direction constantly. Switching the direction resets the enemy's reload.
#### Shoot Up
The enemy shoots upwards after a few frames of reload time.
#### Shoot Turn
The enemy shoots and turns to the next direction available.
#### Parasol
The enemy shoots three times downwards after a few seconds of reload time. Each shot moves the enemy upwards and while it's charging, the enemy moves downwards.