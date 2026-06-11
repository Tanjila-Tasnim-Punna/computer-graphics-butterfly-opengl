# Butterfly Drawing using OpenGL (GLUT)

A simple Computer Graphics lab project that draws a colorful butterfly using OpenGL and GLUT. The butterfly is constructed from multiple colored triangles positioned symmetrically on both sides of the body.

## Features

- 2D butterfly rendering
- Built using OpenGL and GLUT
- Uses multiple colored triangles
- Symmetrical wing design
- Simple beginner-friendly graphics project

## Technologies Used

- C++
- OpenGL
- GLUT (OpenGL Utility Toolkit)

## Project Structure


main.cpp


## How It Works

The butterfly is created by:

- Defining vertex coordinates with `glVertex2i()`
- Drawing triangles using `GL_TRIANGLES`
- Applying colors with `glColor3f()`
- Creating left and right wings through mirrored coordinates
- Using an orthographic projection via `gluOrtho2D()`

## Compilation

### Linux

```bash
g++ main.cpp -o butterfly -lGL -lGLU -lglut
./butterfly
Windows (MinGW)
g++ main.cpp -o butterfly.exe -lopengl32 -lglu32 -lfreeglut
butterfly.exe
Output

The program opens an OpenGL window and displays a colorful butterfly drawn entirely from triangles.

Learning Objectives
Understanding OpenGL primitives
Working with 2D coordinate systems
Using colors in OpenGL
Creating complex shapes from basic geometric objects
Practicing GLUT window management
