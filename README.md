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

