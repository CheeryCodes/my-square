# Welcome to My Square
***

## Task

This program Create a program which displays a beautiful square with customizable dimensions and prints it to the console.

## Description

The program takes two integer arguments from the command line, representing the dimensions of the grid (rows and columns). It then generates a square grid with outer edges marked as "o", top and bottom edges marked as "-", and left and right edges marked as "|". The inner cells are left empty, represented by spaces.

## Installation

1. Ensure you have a C compiler installed on your system (e.g., GCC for Unix-like systems or MinGW for Windows).
2. Download or clone the source code files.
3. Compile the program using the appropriate compiler command. For example:
   
   ```
   gcc my_square.c -o my_square
   ```

## Usage

Run the compiled program from the command line, providing two integer arguments representing the dimensions of the grid:

```
./my_square <rows> <columns>
```

Replace `<rows>` and `<columns>` with the desired dimensions of the grid. For example:

```
./my_square 5 10
```

This command will generate a grid with 5 rows and 10 columns and print it to the console.

