[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15435709&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted programming language known for its readability and simplicity. It emphasizes code readability with its use of significant whitespace and has a straightforward syntax that allows developers to express concepts in fewer lines of code.
   Key features include:
   - Readability 
   - Versatility
   - Extensive libraries
   - Object-oriented programming
   - Dynamic typing
   - Automatic memory management
   Python is widely used in various fields, including:
   - Web development: With django and flask 
   - Data science: With pandas and NumPy
   - Machine learning: TensorFlow and acikit-learn 
   - Automation 
   - Software development.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Steps to Install Python:

    Windows:
        Download the Python installer from the official Python website.
        Run the installer. Make sure to check the box that says "Add Python to PATH" before clicking "Install Now."
        Verify the installation by opening Command Prompt and typing python --version or python -V.
   Setting Up a Virtual Environment:
     python -m venv myenv  # Create a virtual environment
     myenv\Scripts\activate  # Activate the virtual environment (Windows)
   

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   Hello, World! Example:
   print("Hello, World!")
   Explanation:
   'print()' is a built-in function that outputs text to the console.
   "Hello, World!" is a string enclosed in double quotes.
   The statement ends with a newline, not a semicolon.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic Data Types:

    int: Integer values (e.g., 42)
    float: Floating-point values (e.g., 3.14)
    str: String values (e.g., "Hello")
    bool: Boolean values (True or False)
    Example script:
    # Integer
    x = 10
    # Float
    y = 20.5
    # String
    name = "Alice"
    # Boolean
    is_active = True

    print(x, y, name, is_active)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Conditional statements are used to perform different actions based on different conditions. The primary conditional statements in Python are if, elif, and else.
   Loops are used to repeat a block of code multiple times. Python has two main types of loops: for loops and while loops.
   Example if-else statement:
   x = 10
   if x > 5:
   print("x is greater than 5")
   else:
   print("x is less than or equal to 5")
   Example for loop:
   for i in range(5):
   print(i)



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions are reusable blocks of code that perform a specific task. They help in making code modular, easier to maintain, and reusable.
   Example function:
   def sum(a, b):
   return a + b
   # Call the function
   result = add_numbers(5, 3)
   print(result)  # Output: 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Lists are ordered collection of items, defined with square brackets [] while dictionaries are unordered collection of key-value pairs, defined with curly braces {}.
   Example script:
   # List
   numbers = [1, 2, 3, 4, 5]
   print(numbers[0])  # Output: 1

   # Dictionary
   person = {'name': 'John', 'age': 30}
   print(person['name'])  # Output: John

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   It’s a mechanism to handle errors gracefully without crashing the program.
   Example script:
   try:
   x = 10
   y = 0
   z = x / y
   except ZeroDivisionError:
   print("Cannot divide by zero")
   finally:
    print("Execution completed.")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Concepts:

    Module: A file containing Python code, typically with a .py extension.
    Package: A collection of modules in a directory, with an __init__.py file.
    Import: The process of making a module or package available to a script.
    Example script:
    import math
    print(math.pi)  # Output: 3.141592653589793


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   Python provides built-in functions for reading from and writing to files. These operations are typically performed using the open() function, which returns a file object.
   Example script:
   # Read from a file
   with open("file.txt", "r") as file:
   content = file.read()
   print(content)
   # Write to a file
   with open("file.txt", "w") as file:
   file.write("Hello, World!")
   

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


