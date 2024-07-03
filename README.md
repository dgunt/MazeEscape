# Maze Escape



## About the Game

**Maze Escape** is a Unity3D game, where you play as a lonely pill trying to escape a dangerous maze.
Before the game starts, you are greeted by a menu screen that allows you to input the size of the
maze you would like to play in. Your maze can be as small as a tiny 5 by 5 grid, or as large as a 30 by
30 labyrinth!



## Completed Features

### Menu and Maze Generation
- [x] Main menu screen allows the player to input the desired dimensions of the maze.
- [x] During a level, the player can pause at any time, and return to the main menu.
- [x] Random mazes generated at runtime.
  - [x] Recursive division maze generation algorithm coded in Unity from scratch.
- [x] Poisson disk distribution used to scatter rooms, enemies, health, and keys across the maze with uniform randomness.
  - [x] Exactly same number of keys and rooms are generated.
  - [x] Objects are placed randomly but cannot spawn in the same locations.

### Characters
- [x] Player can rotate in the direction of the cursor and fire projectiles on click.
- [x] Bomb enemies created. 
  - [x] Can follow the player's transform and inflict damage upon contact.
  - [x] Can drop bombs that damage the player and destroy walls within their blast radius.
- [x] Fire enemies created.
  - [x] Can shoot projectiles in the direction of the player's transform that inflict damage.
  
### Assets, Animations, and UI
- [x] All 3D models and animations created from scratch in Unity.
- [x] Player and enemies flash while taking damage.
- [x] Player's health bar decreases when the player is damaged and increases after the player finds health.
- [x] All enemies have individual health bars.
- [x] Fire enemies animated with spinning projectiles.
- [x] Collectible items rotate.
- [x] Player and enemies explode upon death.

###

## Directions

Use `WASD` to move around. Your cursor indicates the direction you want to shoot. Left-click to shoot a
pellet. If you have a key, you can use it to unlock a room. Stand next to the door of the room and press
`enter` to unlock the door. Once all rooms have been opened, navigate to the exit in the top-right corner
of the maze.


