## Task 1: Perform Basic Mathematical Operations

**Filename:** `task1.py`

### Problem Statement:
Write a Python program that:
1. Takes two numbers as input from the user.
2. Performs the following operations:
   - Addition
   - Subtraction
   - Multiplication
   - Division
3. Displays the result of each operation clearly.
   
# Take input from the user
```python
   num1 = float(input("Enter first number: "))
   num2 = float(input("Enter second number: "))
# Perform operations
   print(f"Addition: {num1 + num2}")
   print(f"Subtraction: {num1 - num2}")
   print(f"Multiplication: {num1 * num2}")
   print(f"Division: {num1 / num2 if num2 != 0 else 'Cannot divide by zero'}")=

# Task 2: Create a Personalized Greeting

**Filename:** `task2.py`

## Problem Statement
Write a Python program that:
1. Takes a user's first name and last name as input.
2. Concatenates the first name and last name into a full name.
3. Prints a personalized greeting message using the full name.
## Expected Output
The program should output a greeting like:
```python
# Sample Input:
Enter your first name: John
Enter your last name: Doe
# Sample Output:
Hello, John Doe! Welcome aboard.

# Step 1: Take user input
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")
# Step 2: Concatenate names
full_name = first_name + " " + last_name
# Step 3: Print greeting
print(f"Hello, {full_name}! Welcome aboard.")

## How to Run
Make sure you have Python installed. Then run each script using:
```bash
python task1.py
python task2.py



