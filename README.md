# MG3
## Devlog
1. The default value of a float is 0.0, the default value of an int is 0, the default value of a bool is false, and the default value of a string is null. I checked these values by adding member variables of these types to the Timer class and looking at them in the Unity Inspector.

2. The Update() method is a built-in Unity method. Unity calls it automatically every frame while the script is enabled. I do not need to call it myself. A frame is one update cycle of the game. The Update() method can be used to check input, update the timer, and check whether the timer has finished.

3. The KickWeapon class uses a Timer to control how long a kick stays active. When the player presses the spacebar, ActivateKick() activates the kick and calls BeginTimer() to start the countdown. In Update(), the KickWeapon class checks whether the timer has finished. If it has, the kick GameObject is deactivated. This prevents the kick from staying active for too long.
## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
