# ObjectARX - 4(Add a Line to Model Space)

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

- `Exercise-4.cpp`: Entry point function (acrxEntryPoint) for an ObjectARX application. It includes  header files (pch.h, arxHeaders.h, and framework.h). The addLine function is defined to add a line to the AutoCAD drawing. Within acrxEntryPoint, a switch statement handles initialization and unloading of the application. During initialization, the application is unlocked, registered as MDI-aware, and a custom command (addLine) is registered with AutoCAD to execute the addLine function. During unloading, a group of commands is removed. 
