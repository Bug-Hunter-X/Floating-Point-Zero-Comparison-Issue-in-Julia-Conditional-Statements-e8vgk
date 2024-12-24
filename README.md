# Julia Floating Point Zero Comparison Bug
This repository demonstrates a subtle bug related to floating-point comparisons in Julia's conditional statements.  Specifically, the code behaves unexpectedly when comparing to zero using floating-point numbers.

The issue stems from the fact that -0.0 is a valid floating-point number in Julia, which is not strictly equal to 0.0.

The `bug.jl` file contains the buggy code, and `bugSolution.jl` provides a solution that correctly handles both positive and negative zero.
