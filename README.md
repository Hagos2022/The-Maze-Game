# The Maze

The Maze is a 3D game built using SDL and Raycasting. On the map, the player can move in all four directions using keys ```W```, ```A```, ```S```, and ```D```. 

The player can move through the maze and turn left or right as desired.

If the player hits a wall, it  cannot move unless it change its direction.

The player can move on several directions and rotate in the same time.

## Installation

```bash
git clone https://github.com/Hagos2022/The-Maze-Game.git
```

## Compiling
This project makes use of gcc and make for the compilation process.

### Windows
Ensure you have gcc, and make(Can be installed using chocolatey). Then run the following command:

```bash
make
```

### Linux
First make sure SDL is installed. If you haven't install SDL by running ``` make linux_install ```. Then run the following command:

```bash
make linux
```

### Mac
Ensure sdl is installed. Then run the following command:

```bash
make mac
```

## Running
After successfully compiling run the program using the following command:

```bash
./maze MAP
```

where ```MAP``` is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.

## Controls

```W``` - Moving forward

```S``` - Moving backward

```A``` - Look left

```D``` - Look right

```Mouse move left/right``` - look left or right

```M``` - Turn off map visibility. The 2D map won't be visible on clicking

```N``` - Turn on map visibility. The 2D map will be visible again if it wasn't


# Directories

[`src`](https://github.com/candiepih/The-Maze/tree/main/src)

Contains all the source code files written in C.

[`inc`](https://github.com/candiepih/The-Maze/tree/main/inc)

Contains all the header files.

[`maps`](https://github.com/candiepih/The-Maze/tree/main/maps)

Contains map data files. This will be used by the program to output the map layout.

[`images`]()

Contains image files.

# Images

![image](https://user-images.githubusercontent.com/44834632/138765500-bd3838d0-fe46-4018-87b0-21143fb77e8b.png)


## Texture sources

**Weapon**

https://www.seekpng.com/idown/u2w7u2t4i1y3a9y3_call-of-duty-guns-firearms-gun-weapons-coat/

## Contributing


## Related

*[The Maze](https://alx-intranet.hbtn.io/concepts/133)* - Holberton Project Page

## License
**BSD**


# Author

Mehari Hagos [@Hagos2022](https://github.com/Hagos2022) <hagos69@gmail.com>
