# Data structures and Algorithms

## Task 1: Text files
##### General execution requirements:
- Specify input and output file names through the command line or from the keyboard while the program is running;
- Handle open file errors;
- Do not use standard functions with lines like COPY, POS from Pascal;
- Do not overwrite the entire file in RAM.

##### Task condition:
A text file is given. Each line contains no more than 255 characters. Create a new file with the lines in reverse order. The size of the file is not limited. It is forbidden to place the whole file in the main memory. Files of size about 10MB should not take more than 2 seconds to process.

## Task 2: Linear Lists
##### General execution requirements:
- Organize data input from a file in a user-friendly form;
- Provide the possibility of multiple queries without restarting the program;
- When implementing in C++, do not use container classes to work with linear lists like stack, queue, etc.

##### Task condition:
A character string contains an expression of letters and operations in prefix form (the sign of the operation before the operands). Check the correctness of the entry and translate the expression to the postfix form (the sign of the operation after the operands). If there are errors indicate the place of one of them. Example: The expression (a+b)×c-d×e is written in prefix form as -×+abc×de. It is required to output it as ab+c×de×-

## Task 3: Tree structure
##### General execution requirements:
- Enter the source tree from a file in a user-friendly form, not from the keyboard;
- Show the tree on the screen when the user requests it;
- Process the tree in RAM, rather than by repeatedly accessing the file;
- Provide the possibility of multiple queries without re-running the program.

##### Task condition:
The structure of some institute is given by a tree. The sons of the root node correspond to the faculties, in turn are divided into departments, which may have branches. Teachers correspond to the leaves of the tree. Identify the teachers who teach in three or more departments.

## Task 4: Sorting
##### Task condition:
There are N black and one white checker on the chessboard. You need to write a program that determines the maximum number of checkers the white checker can take in one move. Input from input.txt file. There are 8 lines, each line contains 8 characters. Character '0' is an empty cell, character '1' is the position of the black checker and character '2' is the position of the white checker. Output to output.txt file. Output a single number - the maximum number of black pieces that can be taken per move.
