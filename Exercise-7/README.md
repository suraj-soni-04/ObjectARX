# ObjectARX - 7

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

- `Exercise-7.cpp`: Entry point function (acrxEntryPoint) for an ObjectARX application.It includes header files (pch.h, framework.h, dbents.h, and arxHeaders.h). The inputLine function is defined to prompt the user to input two points and then creates a line based on those points in the current space of the AutoCAD drawing. Within acrxEntryPoint, a switch statement handles initialization and unloading of the application. During initialization, the application is unlocked, registered as MDI-aware, and a custom command (inputLine) is registered with AutoCAD to execute the inputLine function. During unloading, a group of commands is removed.
