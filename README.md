# 23085126_mazegame

 MAZE GAME IN C++
 -----------------
 
 DESCRIPTION:
 ------------
 This is the console-based c++ game  where user gets to add the input as per directed by the program. This program has 10x10 grid using 2D array.

 GAME FEATURES:
 --------------
 1. It has 10x10 grid using 2D array.
 2. It has '#' for walls, ' ' for paths, 'P' for Player, 'E' for exit, 'X' for enemy and '*' for collectibles.
 3. Collectibles(*) are to increase the scores.
 4. This game has upto three levels[Easy,Medium and Difficult]
 5. This game starts from level 1  and it gets upgraded when all the '*' are collected.
 6. This game also tracks the multiple levels, scores and moves taken.
 7. This game loads and save in the .txt file later on.
 8. The base class Entity is implemented and class Player gets inherited.
 9. This file have header and source files.
 10. The code also handles the collision hit Players with walls and enemies.

DIRECTIONS:
------------
U = Up directions
D = Down directions
L = Left directions
R = Right directions
E = Exit

FILES:
------
- main.cpp           :This file starts the game, calls the function and loops.
- Grid.cpp/h         :This file display grid, randomly place the enemy and collectibles and count.
- Game.cpp/h         :This file has base class Entity with Player class, movecount and scores.
- collision.cpp/h    :This file has the collision handling with walls and enemy and exit.
- filehandling.cpp/h :This file saves and loads to/from the file into .txt format later on.
- direction.cpp/h    :This file has U/D/L/R AND E functionalities for user in the game.
- README.txt         :Instructions

TO COMPILE:
-----------
1. Open Code::Blocks in your PC.
2. Create a new empty project.
3. Add all the .cpp and .h files to it.
4. Run the main.cpp file
5. Build it and enjoy playing.


- By-APEKSHYA BASHYAL
- STUDENT ID = 23085126

DATE = 04/20/2025

ENJOY THE GAME.
