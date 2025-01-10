# Portfolio
This repository contains all of my note-worthy, large-scale academic code projects. Below you can find a brief summary of each project

**the bash assignment - linux Bash scripting**
the "bn" file is a command-line utility that accepts a name, year and gender as input, and returns the name's ranking against all others matching the specified year and gender. Data is pulled from the text files within the us_baby_names directory.

skills represented: bash scripting, searching and filtering through data, exception handling 

Usage: bn <year> <assigned gender: f|F|m|M|b|B>
use bn --help for more information


**the ci pipeline assignment - C code**
the "quiz.c" file is a command-line utility that plays a quiz game with it's user. if just a question number is input, it will print the question corresponding to that question number. If a question number and an answer is input, feedback wiil be returned indicating whether the answer or not the answer is correct. 

skills represented: C programming, command-line interfacing and exception handling 

Usage: quiz <-#> <answer>
use quiz --help for more information, executable must be created via makefile


**Data Processing assignment - C code**
the "clean.c" file is a command-line utility that, when compiled together with clean.h and cleanfunc.c, creates an executable that can be used to process a two dimensional grid of floating-point numbers and replace all bad values with legal ones. Using the -d flag at runtime will implement a deletion strategy, which will replace all nan values with 0s. If the -d flag is not used, an imputation strategy will be used instead, where all nan values will be replaced with the average value of legal floats in that column.

skills represented: C programming, memory management, array processing and pointer logic

Usage: clean -d <file> or clean <file>
executable must be created via makefile 
