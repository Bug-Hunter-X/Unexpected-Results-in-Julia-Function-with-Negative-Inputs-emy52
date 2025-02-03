# Julia Function Bug: Unexpected Results with Negative Inputs

This repository demonstrates a subtle bug in a Julia function that produces unexpected results when dealing with negative inputs.  The issue stems from operator precedence, which leads to incorrect calculations.

## Bug Description

The `myfunction` function aims to return the square of the input if positive, 0 if zero, and the negative of the square if negative. However, due to a precedence issue, the negative sign is applied after the squaring operation for negative inputs.

## How to Reproduce

1. Clone this repository.
2. Run `bug.jl` using the Julia interpreter.
3. Observe that the output for the negative input is incorrect.

## Solution

The `bugSolution.jl` file provides a corrected version of the function, addressing the precedence issue using parentheses.

## Contact

For questions or feedback, please open an issue on this repository.