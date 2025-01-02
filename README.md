# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: forgetting to handle negative input values.  The `factorial` function correctly calculates the factorial for non-negative integers but raises a `RecursionError` when given a negative input because the recursion never terminates.

The `bugSolution.py` file shows how to fix this by adding a check for negative input and raising a `ValueError` instead of attempting to calculate the factorial of a negative number. 