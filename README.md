## PYTHON PROGRAMMING MODULE 03
## NAME : PREETHI D
## REGISTER NUMBER : 212224040250

# EXP 01 -List Operations in Python: Sum of List Items

##  Aim
To write a Python program that calculates the **sum of all elements** in a list.

##  Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

##  Program
```
numbers = [25,22,10,6]
total = sum(numbers)
print("The sum of all elements in the list is:", total)
```
## Output
![image](https://github.com/user-attachments/assets/fac20bfa-efda-4eff-986e-95e813fa7c00)

## Result
Therefor the given Python Program has been executed successfully and the output has been verified.

# EXP 02 - Regex in Python: Filter Words Without the Letter 'e'

##  Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

##  Program
```
import re

l1 = []

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Words without the letter 'e':", l1)
```
## Output
![image](https://github.com/user-attachments/assets/c1d756f1-1bf7-4a3a-a309-dc82300ca159)

## Result
Therefore the Python program has been executed successfully and the output has been verified.
