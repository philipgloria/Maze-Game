# The 3D_Maze Game
![maze gif](https://user-images.githubusercontent.com/88714347/171422634-8adc8811-2559-4ba1-967f-4caf909c3f22.gif)
- This repository contains the files to launch a A First Person's view Game with the aid of Raycasting, It's respective data collection and arrangement to setup and manage a 3D Maze Environment. It uses seperated functions which are connected to various motion, interaction and view operations, It is reasonably short and easy to comprehend.

- This MazeGame is a mini project written in C programming language using SDL2 Library that gives the user a virtual interface well laced with critical functionalities enabling robust movement and interactions.

- The development of this maze game  was performed using codeblocks with the required SDL2 Libraries.

- The game is also funtional on an Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- This maze game runs on all platforms Windows, Mac OS X and Linux/Ubuntu.
# About SDL2
![Maze Game](https://miro.medium.com/v2/resize:fit:720/format:webp/1*-24ykcYYrPI2xlWn2HdSFA.png)
- Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games. for more information on [SDL2](https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer)

# Requirements to Play
  - Linux/ubuntu or Macos
  - SDL2 and its sdl_image
# Installation

## Sdl2 installation
  - Download the installation script [install_SDL2.sh](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/graphics_programming/install_SDL2.sh) and run it in your ubuntu Terminal as follows:
- `root@h:cd ~/Downloads$ ls`
- `install_SDL2.sh`
- `root@h:cd ~/Downloads$chmod 755 install_SDL2.sh`
- `root@h:cd ~/Downloads$sudo ./install_SDL2.sh`

# Play the game
 - clone the [github repository](https://github.com/Hoffdl/Maze-Project.git)
 - Compile all .c files in the maze directory:
  ```
  gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm $(sdl2-config --cflags --libs) -lSDL_image -o maze
   ```
 - Execute ./maze and play game.
 - Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
 - Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)
# Controls
 W or up arrow key - Moving forward
 S or down arrow - Moving backward
 left arrow key - to rotate the player in counter clock wise direction
 right arrow key - to rotate the player in clock wise direction

# Flow chart
![Capture](https://user-images.githubusercontent.com/88714347/171421868-d6a7a3d6-6acd-495e-9506-7ab381bba5a4.JPG)
# project Demo
 [![3D Maze](https://img.youtube.com/vi/y5FlT2oApag/0.jpg)](https://www.youtube.com/watch?v=y5FlT2oApag)
