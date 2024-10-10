# Day 1: DataType Operators

## Objective
Today, we're discussing data types. Check out the Tutorial tab for learning materials and an instructional video!

## Task
Complete the code in the editor below. The variables , , and  are already declared and initialized for you. You must:

1. Declare  variables: one of type int, one of type double, and one of type String.
2. Read  lines of input from stdin (according to the sequence given in the Input Format section below) and initialize your  variables.
3. Use the  operator to perform the following operations:
  1. Print the sum of  plus your int variable on a new line.
  2. Print the sum of  plus your double variable to a scale of one decimal place on a new line.
  3. Concatenate  with the string you read as input and print the result on a new line.

## Input Format

1. The first line contains an integer that you must sum with.
2. The second line contains a double that you must sum with.
3. The third line contains a string that you must concatenate with d.

## Output Format

Print the sum of both integers on the first line, the sum of both doubles (scaled to  decimal place) on the second line, and then the two concatenated strings on the third line.

## Solution
```
i = 4
d = 4.0
s = 'HackerRank '
Declare second integer, double, and String variables.
i = 4
d = 4.0
s = "HackerRank"

Read and save an integer, double, and String to your variables.
'''
int_var = int(input())
Double_var = float(input())
str_var = input()

Print the sum of both integer variables on a new line.
print(i + int_var)

Print the sum of the double variables on a new line.
print(format(d + Double_var, '.1f'))
Concatenate and print the String variables on a new line
The 's' variable above should be printed first.
print(s +' '+ str_var)
```
