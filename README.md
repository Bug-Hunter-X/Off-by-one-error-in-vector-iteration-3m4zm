# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The provided code attempts to print the elements of the vector, but due to an incorrect loop condition, it accesses an element beyond the valid range, resulting in undefined behavior.

The `bug.cpp` file contains the erroneous code.  The solution, illustrating how to fix the error, is presented in `bugSolution.cpp`.