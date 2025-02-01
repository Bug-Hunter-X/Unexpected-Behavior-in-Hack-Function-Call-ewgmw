# Hack Function Call Bug

This repository demonstrates a subtle bug related to function calls in Hack. The `bar` function is expected to return `(x + 1) * 2`, but due to an unusual interaction with type inference and function calls, it may not produce the correct result in all cases.  The bug is highlighted in `bug.hack`, and the solution is provided in `bugSolution.hack`.  This example highlights potential edge cases when dealing with function calls and type inference in Hack.

## Running the Code

To reproduce the bug and run the solution, you will need the Hack compiler and runtime environment.  Instructions for setting up your environment are available on the official Hacklang website.