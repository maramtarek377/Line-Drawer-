# VTK GUI for Drawing Straight Lines #
This VTK GUI allows you to draw a straight line by clicking the mouse once to indicate the starting point and another click indicates the ending point. In addition, it shows the coordinates of the last clicked position. This is a simple example of how to use the VTK library to create a graphical user interface with minimal code.

## Dependencies ##
* VTK (version 9 or higher)
* CMake (version 3.1 or higher)

## Build ##
To build the application, follow these steps:

1. Clone the repository to your local machine.
2. Create a new directory called "build".
3. Change to the "build" directory.
4. Run 'cmake ..' to configure the build.
5. Run 'make' to build the application.

## Usage ##
To use the application, simply run the executable built in the "build" directory. Once the application is running, you can draw a straight line by following these steps:

1. Click the left mouse button to indicate the starting point of the line.
2. Move the mouse to the desired ending point of the line.
3. Click the left mouse button again to indicate the ending point of the line.
4. The straight line will be drawn on the screen using VTK's 'vtkLineSource' class.
