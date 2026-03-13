# C Lab: Lists and Stacks Exercises

## Project Overview
This is a C programming lab focused on exercises using List (ArrayList) and Stack data structures. Students implement functions in `exercises.c` and test them by running `bash test.sh` in the terminal.

## Structure
- `exercises.c` - Student implementation file (the only file students should modify)
- `arraylist.h` / `arraylist.c` - ArrayList TDA implementation
- `stack.h` - Stack TDA header
- `test.c` - Test suite (do not modify)
- `test.sh` - Build and test runner script

## Running Tests
Open the Shell and run:
```bash
bash test.sh
```

## Build System
- Language: C
- Compiler: GCC
- No build system (direct gcc compilation)
- Compile command: `gcc -g test.c -Wall -Werror -o a.out`

## Important Notes
- Only `exercises.c` should be modified by students
- No frontend or backend server — this is a pure C console project
- The workflow compiles and provides a shell for running tests
