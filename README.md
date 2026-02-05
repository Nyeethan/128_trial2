# Exercise 1: Computing a serial solution to a given problem P

A C implementation of an algorithm that will compute for the columnar Z-Score Normalization (ZSN) of an n x n matrix.

## Setup

### Check if GCC is installed
gcc --version


## Testing

### Step 1: Save the code

Make sure to save the program as (filename).c in your working directory.

### Step 2: Compile the program

Compile the program as:
gcc -O3 -o (executable filename) (filename).c -lm
- '-03' - to ensure maximum optimization level
- '-lm' - to link the math library

### Step 3: Running the program

Run as follows:
./(<executable filename) (size of the n x n matrix)