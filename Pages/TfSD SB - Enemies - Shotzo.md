## Shotzo
![[TfSD SB - Image - Enemies - Shotzo.png]]
[[TfSD SB - Enemy Categories - Normal|Enemy Category - Normal]]

An invincible, stationary cannon that shoots at the player, usually pausing after three consecutive shots.
### AI States
#### Follow Player
The enemy's aim follows the player in 5 directions and when it's locked in, they shoot to that direction constantly. Switching the direction resets the enemy's reload.
#### Shoot Straight
The enemy shoots straight to their direction after a few seconds of reload time.
#### Bounce and Attack
The enemy bounces a tile above and does a three-way attack. Both actions are asynchronous.
#### Shoot Up
The enemy shoots three times upwards after a few seconds of reload time.
#### Shoot Turn
The enemy shoots and turns to the next direction available.
#### Shoot Up
The enemy shoots three times downwards after a few seconds of reload time. Each shot moves the enemy upwards and while it's charging, the enemy moves downwards.