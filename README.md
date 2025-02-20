# Python Code Bug: ZeroDivisionError in Average Calculation

This repository demonstrates a common coding error in Python: a `ZeroDivisionError` that can occur when calculating the average of a list of numbers. The bug occurs when an empty list is provided as input to the `calculate_average` function.

## Bug Description

The `calculate_average` function calculates the average of a list of numbers. However, if the input list is empty, it attempts to divide by zero, resulting in a `ZeroDivisionError`. This bug is addressed by adding a condition to explicitly check for an empty list and return 0 in that case. 

## Bug Solution

The solution involves adding a check for an empty list at the beginning of the `calculate_average` function. If the list is empty, the function returns 0; otherwise, it proceeds with the calculation.
