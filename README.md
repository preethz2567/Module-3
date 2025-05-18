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


# EXP 03-Strings-Remove Nth Index Character from a String

##  Aim
To write a Python program that accepts a string and removes the character at a specified index.

##  Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

##  Program
```
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    
    return a

input_str = input("Enter a string: ")
result = remove(input_str)
print("String after removal:", result)
```
## Output
![image](https://github.com/user-attachments/assets/459ab746-af06-4208-b9f6-ce905641e5bf)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.
# EXP 04- Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## Program
```
s = "google"
rev = s[::-1]
if s == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
![image](https://github.com/user-attachments/assets/69144367-a1f4-4b4f-b816-1abca2d04fd8)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.

# EXP 05-Tuple in Python: Check Element Existence

##  Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

##  Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

##  Program
```
x = ('a', 'b', 'n', 5, 8, 'z')

if 'n' in x:
    print("'n' is present in the tuple.")
else:
    print("'n' is not present in the tuple.")


if 8 in x:
    print("8 is present in the tuple.")
else:
    print("8 is not present in the tuple.")

```
## Output
![image](https://github.com/user-attachments/assets/50fbf17f-28ea-471f-aec6-eed8cfac3fe1)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.
