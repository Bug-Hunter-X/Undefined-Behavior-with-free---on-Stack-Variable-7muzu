# Undefined Behavior with free() on Stack Variable

This repository demonstrates a common C programming error: attempting to free memory allocated on the stack using `free()`.  The `free()` function is intended for deallocating memory that was dynamically allocated using functions like `malloc()`, `calloc()`, or `realloc()`. Attempting to `free()` memory not allocated with these functions leads to undefined behavior, which can manifest in various ways (crashes, unexpected results, etc.).

The `bug.c` file shows the erroneous code, while `bugSolution.c` offers a corrected version.