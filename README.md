FeOSolver
=========

Introduction
------------

FeOS is a free, open-source sudoku solver for the Nintendo DS.

Build prerequisites
-------------------

You need the following in order to build FeOS:

- devkitARM r34 or higher
- libnds 1.5.2 or higher
- libfat 1.0.10 or higher
- The current FeOS SDK

Before building, you must set the `FEOSSDK` environment variable to point to the `/sdk` directory (if on Windows, you **must** use Unix-style paths, like `/c/Users/.../gitrepos/FeOS/sdk`).

How to build FeOSolver
----------------------

`cd` to the directory this repo is in and type the following:

    make

When it's done compiling, transfer the generated `feosolver.fx2` to `data/FeOs/bin` on your SD card.

How to use FeOSolver
--------------------

Start FeOSolver by typing `feosolver` on FeOS cmd prompt.
Enter a 81-character string representing a sudoku.
Use `.`, `0` or the space bar for emty fields.
Press enter.