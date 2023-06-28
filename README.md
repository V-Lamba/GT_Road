# GT_Road
A 2D Car Racing game developed using XCode.

Graphic libraries like OpenGL and GLUT are required to run main.cpp

Introduction to Project
The game's objective is to navigate your car through three lanes and obstacles i.e. another car is running opposite us. The main goal of the player is to maximize their score and pass as many levels as possible. The game will be displayed in a window using OpenGL graphics, and the player will control the car using keyboard arrow keys.

Here are some of the main components of the game:

1. Game environment: The game environment will consist of a 2D track of three lanes and obstacles, such as other cars, that the player needs to avoid. The track is created using OpenGL primitives such as lines and polygons.
2. Car model: The car model is a simple 2D rectangle and triangle at the top with four rectangles at its side that can be considered its wheels. It can be moved around the track using the keyboard input arrow keys only. The car is created using a combination of OpenGL primitives such as rectangles and triangles.
3. User interface: The user interface will display the game score, level, instructions, speed, and other important information. It can be created using simple 2D text and GUI elements.
4. Game physics: The game physics will control the car's movement and other game objects. It can be implemented using simple physics formulas such as decreasing the frame rate per second, which can be considered the car's speed.
