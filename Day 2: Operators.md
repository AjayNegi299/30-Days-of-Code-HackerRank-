## Task
Given the meal price (base cost of a meal), tip percent (the percentage of the meal price being added as tip), and tax percent (the percentage of the meal price being added as tax) for a meal, find and print the meal's total cost. Round the result to the nearest integer.

## Example
1. meal_cost_percent = 100.
2. tip_percent = 15.
3. tax_percent = 8.

A tip of 15% * 100 = 15, and the taxes are 8% * 100 = 8. Print the value  and return from the function.

## Function Description
Complete the solve function in the editor below.

solve has the following parameters:

1. int meal_cost: the cost of food before tip and tax.
2. int tip_percent: the tip percentage.
3. int tax_percent: the tax percentage.
4. Returns The function returns nothing. Print the calculated value, rounded to the nearest integer.

## Solution
```
#!/bin/python3

import math
import os
import random
import re
import sys

#
# Complete the 'solve' function below.
#
# The function accepts following parameters:
#  1. DOUBLE meal_cost
#  2. INTEGER tip_percent
#  3. INTEGER tax_percent
#

def solve(meal_cost, tip_percent, tax_percent):
    tip = meal_cost * tip_percent / 100
    tax = meal_cost * tax_percent /100
    totalCost = meal_cost + tip + tax
    print(round(totalCost))
 

if __name__ == '__main__':
    meal_cost = float(input().strip())

    tip_percent = int(input().strip())

    tax_percent = int(input().strip())

    solve(meal_cost, tip_percent, tax_percent)

   ``` 
    
    
    
    
