# ObjectARX - 1(Create a New Project from Scratch)

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

- `Exercise-1.cpp`: Entry point function (acrxEntryPoint) for an ObjectARX application. The MyCommand function is declared, presumably to execute a custom command within AutoCAD. Within acrxEntryPoint, there's a switch statement to handle initialization and unloading of the application. During initialization, the application is unlocked, registered as MDI-aware, and a custom command (MyCommand) is registered with AutoCAD. During unloading, a group of commands is removed. 
