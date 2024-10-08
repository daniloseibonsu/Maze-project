# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 24.04 - gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Installation 
```sh
$ git clone https://github.com/daniloseibonsu/Maze-Project.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)


## Author :black_nib:

- **Daniel Osei Bonsu ** <[Daniel](https://github.com/daniloseibonsu@gmail.com)>
- 
- **LinkedIn** <[Daniel](https://www.linkedin.com/in/daniel-bonsu-8a81791b9/)>

- ##  Screenshot
- <[Maze](https://docs.google.com/document/d/19_C-fWaGfkoZ2qQS1JLEsWveCpd1NwNUIQdlLSfgB2c/edit?usp=sharing)>
