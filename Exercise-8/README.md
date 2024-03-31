# ObjectARX - 8(Select Objects and Request a Keyword)

## Structure

The project is structured as follows:

- `src`: This directory contains the source code files.
- `headers`: This directory contains the source code files.
  <hr>

## Files

- `pch.h`: This is a precompiled header file containing headers that are pre-compiled to improve build performance.

- `framework.h`: Header file including MFC core and standard components.

- `Resource.h`: Resource file with default values for new objects.

- `dllmain.cpp`: Defines the initialization routines for the DLL.

- `Exercise-8.cpp`: Entry point function (acrxEntryPoint) for an ObjectARX application. It includes header files (pch.h, framework.h, dbents.h, and arxHeaders.h). The changeColor function is defined to prompt the user to select objects and change their color. Within acrxEntryPoint, a switch statement handles initialization and unloading of the application. During initialization, the application is unlocked, registered as MDI-aware, and a custom command (changeColor) is registered with AutoCAD to execute the changeColor function. The changeColor function utilizes AutoCAD's selection set functionality and prompts the user to enter a color keyword. It then iterates through the selected objects, changes their color based on the user's input, and closes them. During unloading, a group of commands is removed. 
