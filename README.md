# AGD_Project
 Unreal Engine 4 Game demo project for Advanced Game Development (AGD) course.
 Using TwinStickShooter template as initial inspiration I created a snake game where the player can also shoot objects that get in their way.
 - Explanation video: https://www.youtube.com/watch?v=1A4sbVQ9Sk8
 
 Elements used in this project:
 1. Multiplatform: Android, Windows  (Game is playable on both platforms)
 2. Plugins: ItemSpawnerPlugin  (a Box that generates items within it)
 3. Localization: English, Estonian, Japanese
 
 Additionally:
 User Interface elements for navigation between levels and instructions 
 
 ----
 # How to play:
 - On Windows: Use WASD for movement and left mouse button or spacebar to shoot projectiles at cubes. 
 - On Android: use left virtual stick and button on right side to shoot.
 
 * Gain points by collecting yellow balls
 * You die if you crash:
 1. into your tail (made out of white balls) 
 2. other obstacle (walls, cubes)
 
 Tips: 
 In this version it is possible to move between your tail elements if you move fast enough - can help you get through tricky situations. 
 You can vary your speed by holding down or releasing your movement
 The cube obstacles have health so you can get rid of them by shooting.
 
 ----
 # Notes: 
- To make languages work, this needs to be either compiled to an executable or has to be run as Standalone in editor
- Building a Windows executable or Android should work normally, no extra steps needed.
 
 ---
 Song used: Edge of Tomorrow.  Source: http://teknoaxe.com/Link_Code_3.php?q=1242 (Creative Commons Attribution 4.0 International License)
 
 ---
 # For Game Development Patterns course:
- Explanation video: https://www.youtube.com/watch?v=1A4sbVQ9Sk8

* Added 5 integration tests (functional tests) which check:
1. If the pickup ball exists in the level
2. If pawn is moving
3. If shooting spawns a bullet
4. If tail's length equals point count
5. If shooting the obstacle destroys the obstacle

Usage of patterns: Observers (Event Dispatchers), Subclass Sandbox (Inheritance)

---
 
