C Preprocessor Program

Description

This project demonstrates the use of the C Preprocessor. It shows how macros are expanded and how a C source file can be preprocessed to generate an ".i" output file.

Features

- Uses object-like macros
- Uses function-like macros
- Demonstrates macro expansion
- Generates a preprocessed ".i" file
- Removes unnecessary comments from the preprocessed output

Macros Used

#define A 10
#define B 20
#define SUM(a,b) (a+b)
#define SQUARE(x) (x*x)

Expected Output

x = 10
y = 20
z = 30
s = 25

Compilation and Preprocessing

To generate the preprocessed output file:

gcc -E -P program.c -o output.i

Explanation

- "gcc" — GNU C Compiler
- "-E" — Performs only preprocessing
- "-P" — Removes unnecessary line-marker directives
- "program.c" — Input C source file
- "output.i" — Generated preprocessed output file

The generated "output.i" file contains the code after preprocessing and macro expansion.

