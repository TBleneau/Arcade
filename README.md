# Arcade
RetroGaming Platform

./arcade ./lib_arcade_{LIBRARY_NAME}.so
----------------------------------------  

Arcade is a retrogaming platform that lets the user choose a game to play. The user has the choice between three games (Nibbler, Pacman, SolarFox). Arcade permit also to keep the players scores.  

The Goal of this project :
--------------------------

The main feature of this project is to being able to change of game and/or graphic library anytime you want.
Two games and three graphical libraries are already implemented. If you want to build your own just refer to the documentation (located in the doc folder)  

Graphical Libraries :
---------------------

| Libraries   | Description                                                                                                                                                |
| ----------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ncurses** | programming library providing an API that allows the programmer to write text-based user interfaces in a terminal-independent manner                       |
| **Allegro** | cross-platform library mainly aimed at video game and multimedia programming                                                                               |
| **SDL2**    | cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D |

Important ! The program need to be launch with a graphical library.  

Game Libraries :
---------------------

* Nibbler
* Pacman
* SolarFox

The user has the choice between this list of games.  

Global commands :
-----------------

| Commands   | Description                                             |
| ---------: | ------------------------------------------------------- |
| **E**      | Previous graphical library                              |
| **Z**      | Next graphical library                                  |
| **ESCAPE** | While in game, the command return to the selection menu |
| **Q**      | While in game, the command quit the program             |


Game commands :
-----------------

| Commands      | Description             |
| ------------: | ----------------------- |
| **Arrow Key** | Move your character     |
| **S**         | Restart your game       |
| **SPACE**     | To pause the game       |
| **A**         | Go to the previous game |
| **Z**         | Go to the next game     |

