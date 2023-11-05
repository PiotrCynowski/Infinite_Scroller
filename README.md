### Infinite Scroller 
The game was created using Unity Engine.

*gameplay*

![alt text](https://github.com/PiotrCynowski/Infinite_Scroller/blob/master/pic/Gameplay.png?raw=true)

#### Main scene directory:
Assets/Scenes/Main.unity

for game tools go to Testing/UtilsTools

*example of utils*

![alt text](https://github.com/PiotrCynowski/Infinite_Scroller/blob/master/pic/utilsExample.png?raw=true)

To use the tools, the game must be running and the player with the Player Interaction Collision script should have a Player tag

There are 5 prefabs in the main scene:
#### - Player
*with animated 3d model and player scripts*

Plane is controlled by mouse, his position is being adjusted to Y position of a mouse

#### - Background
*scrollable background with separate parallax elements*

#### - SpawnCollObjectsManager
*manager for spawning obstacles and powerups*

#### - CanvasMain
#### - AudioManager

#### - REQUIRED IN SCENE
*Main Camera with MainCamera tag*
