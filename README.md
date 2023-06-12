# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
git clone https://github.com/CheropS/The-Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Contributing
To contribute to the project, kindly git clone and request collaboration on Github. 

## Compilation
```sh
gcc -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`
```

## Flowchart
//![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)*/

## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://www.youtube.com/embed/6T2N8gNUTQ8)
