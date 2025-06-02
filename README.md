# codewars-knowledge-check
# Codewars Solutions

This repository contains solutions to some popular Codewars challenges.

---

## Challenge 1: Even or Odd

**Problem:**  
Create a function that checks if a given number is even or odd.

**Solution:**
```python
def even_or_odd(number):
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"
Example Usage:

python
Copy
Edit
print(even_or_odd(4))  # Output: "Even"
print(even_or_odd(7))  # Output: "Odd"
Challenge 2: Convert a Number to a String
Problem:
Create a function that converts a number into a string.

Solution:

python
Copy
Edit
def number_to_string(num):
    return f"{num}"
Example Usage:

python
Copy
Edit
print(number_to_string(123))   # Output: "123"
print(number_to_string(-100))  # Output: "-100"
Challenge 3: Remove String Spaces
Problem:
Create a function that removes all spaces from a string.

Solution:

python
Copy
Edit
def no_space(x):
    return x.replace(" ", "")
Example Usage:

python
Copy
Edit
print(no_space("8 j 8   mBliB8g  imjB8B8  jl  B"))
# Output: "8j8mBliB8gimjB8B8jlB"

otes
Each function is concise and directly addresses the problem statement.

The solutions use straightforward approaches for clarity and performance.

