# CodeClauseInternship_calculator 
# Simple Python Calculator

## Overview

This is a basic command-line calculator program written in Python. It allows the user to perform four arithmetic operations: addition, subtraction, multiplication, and division. The program displays a menu with options for each operation and continues running until the user chooses to quit.

## Code Description

### Function Definitions

The code defines four functions for performing the arithmetic operations:

- `add(x, y)`: Returns the sum of two numbers.
- `subtract(x, y)`: Returns the difference between two numbers.
- `multiply(x, y)`: Returns the product of two numbers.
- `divide(x, y)`: Returns the result of dividing two numbers. It checks for division by zero and returns an error message if the denominator is zero.

### Main Program Loop

The main part of the program is a `while` loop that runs indefinitely until the user chooses to quit. Inside the loop, it displays a menu of options for the user to select from:

- "add" for addition
- "subtract" for subtraction
- "multiply" for multiplication
- "divide" for division
- "quit" to exit the program

Based on the user's choice, the program takes two numbers as input from the user, calls the appropriate function to perform the selected operation, and stores the result in the `result` variable. If the result is a whole number, it is converted to an integer using the `int()` function. Finally, the program displays the result to the user.

### Error Handling

The code checks for invalid user input and provides an "Invalid input" message if the user enters anything other than the specified options. It also checks for division by zero when performing division and displays a "Cannot divide by zero" error message in such cases.

### Exiting the Program

To exit the program, the user can input "quit," which breaks out of the main loop, terminating the program.

## Usage

To use this calculator program, you can save the code in a Python file (e.g., `calculator.py`) and run it in a Python environment. Follow the on-screen prompts to perform arithmetic operations and quit the program when finished.
