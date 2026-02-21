# Cyan Star using Triangles (OpenGL)

## Project Title

Draw One Cyan Colored Star (built only with triangles) with Yellow Background

## Description

This project demonstrates how to draw a cyan colored star using only triangles in OpenGL. The star is created by overlapping two triangles — one upright triangle and one inverted triangle. The background of the window is set to yellow to provide clear visual contrast with the cyan star.

The program also includes interactive functionality. The window title is set to the student's full ID, and the window closes when the user presses the initial letter of their name on the keyboard.

This project helps understand the fundamental concepts of OpenGL such as vertex definition, triangle rendering, coordinate positioning, color setting, and keyboard input handling.

## Objective

* To learn how to draw shapes using triangles in OpenGL
* To understand how complex shapes like stars can be formed from basic primitives
* To apply color to objects and background
* To implement keyboard interaction to close the window

## Tools and Technologies Used

* Programming Language: C++
* Graphics Library: OpenGL
* Window Management: GLFW / GLUT
* Development Environment: CodeBlocks / Visual Studio / Any C++ IDE

## Implementation Details

The star is constructed using two triangles:

1. Upright Triangle
2. Inverted Triangle

These triangles overlap at the center to form a six-point star.

Each triangle is defined using three vertices. So total vertices used:

2 triangles × 3 vertices = 6 vertices

The star color is set to cyan using RGB values:
Red   = 0.0
Green = 1.0
Blue  = 1.0

The background color is set to yellow using RGB values:
Red   = 1.0
Green = 1.0
Blue  = 0.0

## User Interaction

* Window title displays the full student ID
* Pressing the initial letter of the student's name closes the window

Example:
If the name starts with F, pressing F will close the window.

## How It Works

Step 1: Initialize OpenGL window
Step 2: Set window background color to yellow
Step 3: Define triangle vertices for the star
Step 4: Render the triangles using OpenGL
Step 5: Apply cyan color to the star
Step 6: Listen for keyboard input to close the window

## Output

The program displays:

* Yellow background
* Cyan colored star in the center
* Window titled with student ID

## Learning Outcome

After completing this project, the following concepts are understood:

* Drawing shapes using triangles
* Using vertex coordinates
* Creating complex shapes from simple primitives
* Setting object and background colors
* Handling keyboard input in OpenGL
* Basic OpenGL rendering pipeline

## Conclusion

This project successfully demonstrates how to create a cyan colored star using only two triangles in OpenGL. It shows that complex geometric shapes can be formed using simple primitives like triangles. The use of color improves visualization, and keyboard interaction enhances user control. This experiment strengthens the basic understanding of OpenGL rendering, vertex usage, and graphical programming fundamentals.

## Student Information

Student ID: 0432320005101096
Project: Cyan Star using Triangles
Language: C++
Library: OpenGL

---
