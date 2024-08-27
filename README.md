Creating an AutoCAD-like 2D application using C++ with a custom engine named "AkashEngine" is a complex project. Here's an outline of the steps you might follow to develop this application:

1. Set Up the Environment
open it with visual studio
Set up a project structure with directories for source code, headers, assets, and libraries.
then build it
3. Design AkashEngine
Core Components:
Graphics Renderer: Handle drawing of basic shapes (lines, rectangles, circles, etc.).
Input Handling: Capture mouse clicks, key presses, and other inputs.
Event System: Manage user interactions and update the canvas accordingly.
Entity System: Manage drawable objects on the canvas.
File System: Implement saving and loading of drawing files.
Data Structures:
Use structs to represent points, shapes, and other entities.
4. Implement Basic Features
Drawing Tools:
Line Tool: Click and drag to draw lines.
Rectangle/Circle Tool: Click and drag to draw rectangles or circles.
Selection Tool: Select and move objects.
Grid System:
Implement a grid to assist with alignment.
Zoom and Pan:
Implement zoom in/out and panning across the canvas.
Undo/Redo System:
Allow undoing and redoing actions.
Layer System:
Implement layers to manage different parts of the drawing independently.
5. Rendering
Use the chosen graphics library to render shapes.
Implement double-buffering to avoid flickering during rendering.
6. User Interface (UI)
Menus and Toolbars: Provide easy access to tools and actions.
Canvas: Create a main area where drawing is done.
Status Bar: Show information like cursor position, selected tool, etc.
7. File Operations
Implement functions to save the current drawing to a file and load it later.
Consider using a simple format like JSON or XML for storing drawing data.
8. Testing
Write unit tests for core functions.
Test the application with various scenarios to ensure stability.
9. Optimization
Profile the application to identify and optimize performance bottlenecks.
Implement efficient data structures for managing large drawings.
10. Documentation
Document the code and provide user manuals for the application.
11. Future Enhancements
Add support for more complex shapes and curves.
Implement a plugin system to extend functionality.
Add 3D drawing capabilities if needed.


https://github.com/user-attachments/assets/db5b1680-272f-4535-ab69-46c37c50feb8

