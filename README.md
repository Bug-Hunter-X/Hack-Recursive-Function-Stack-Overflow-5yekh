# Hack Recursive Function Stack Overflow

This repository demonstrates a common error in recursive functions written in Hack: stack overflow. The `foo()` function calculates the factorial of a number using recursion.  However, if a large number is passed as input, the recursive calls consume too much stack space, leading to a stack overflow.

The `bug.hack` file contains the buggy code, while `bugSolution.hack` provides a solution using iteration to avoid stack overflow issues. 