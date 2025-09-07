# Python Basics Repository

This repository contains a structured introduction to core Python programming concepts. Each folder introduces a specific topic with example code and explanations.

## 📁 01_setup
This section covers the initial setup required for running Python. It includes:
- Instructions on installing Python
- Setting up a virtual environment
- Recommended tools and editors

## 📁 02_python_syntax
An overview of Python's basic syntax. Topics include:
- Indentation and code blocks
- Comments
- Printing output
- Basic input/output operations

## 📁 03_variables
This folder explains how to work with variables in Python, including:
- Variable declaration and assignment
- Naming conventions
- Dynamic typing

## 📁 04_typecasting
Covers how to convert data from one type to another in Python. Includes:
- Implicit vs explicit typecasting
- Common type conversion functions (`int()`, `str()`, `float()`, etc.)

## 📁 05_user_input  
Focuses on getting input from users during program execution. Topics include:  
- Using the `input()` function  
- Reading and storing user input  
- Type conversion of input data  
- Simple interactive programs

## 📁 06_comments_print_esc
This section focuses on comments, the `print()` function, and escape sequences in Python. It includes:
- Single-line and multi-line comments
- The `print()` function syntax and usage
- Using `sep` and `end` parameters in `print()`
- Common escape sequences (`\n`, `\t`, `\\`, `\"`, etc.)

## 📁 07_operators
Introduces different types of operators available in Python. Topics include:
- Arithmetic operators (`+`, `-`, `*`, `/`, `//`, `%`, `**`)
- Comparison operators (`==`, `!=`, `>`, `<`, `>=`, `<=`)
- Logical operators (`and`, `or`, `not`)
- Assignment operators (`=`, `+=`, `-=`, etc.)
- Bitwise operators (`&`, `|`, `^`, `~`, `<<`, `>>`)
- Operator precedence and associativity

## 📁 08_conditional
This section covers conditional statements in Python, which allow programs to make decisions based on conditions. It includes:
- **If Statement** – Executing code only when a condition is true
- **If-Else Statement** – Handling both true and false conditions
- **If-Elif-Else Statement** – Checking multiple conditions in sequence
- **Match-Case Statement** – A structured alternative to multiple if-elif blocks (introduced in Python 3.10)

## 📁 09_loops
This section introduces looping constructs in Python, which allow repeating tasks efficiently. It includes:
- **For Loops** – Iterating over sequences like lists, strings, and ranges
- **While Loops** – Running code repeatedly while a condition is true
- **Infinite Loops** – Loops that run indefinitely until manually stopped
- **Break Statement** – Exiting a loop prematurely
- **Continue Statement** – Skipping the current iteration and continuing with the next
- **Pass Statement** – A placeholder statement that does nothing, often used for code structure

## 📁 10_string
This section covers working with strings in Python, one of the most commonly used data types. It includes:
- **String Basics** – Creating and using strings
- **Indexing** – Accessing individual characters in a string
- **Slicing** – Extracting parts of a string using slice notation
- **String Methods** – Built-in methods for string manipulation (e.g., `upper()`, `lower()`, `strip()`, `replace()`, etc.)
- **F-Strings** – Formatting strings efficiently using f-string syntax

## 📁 11_function
This section explains how to create and use functions in Python for reusability, modularity, and cleaner code. It includes:
- **Function Basics** – Defining and calling functions
- **Function Arguments** – Positional, keyword, default, and variable-length arguments
- **Lambda Functions** – Writing small anonymous functions
- **Recursion** – Functions that call themselves
- **Modules** – Organizing code into reusable files (`mymodule.py` example)
- **Function Scope** – Understanding local and global scope
- **Global Keyword** – Modifying global variables inside functions
- **Docstrings** – Writing documentation strings for functions

## 📁 12_lists
This section covers Python lists, one of the most versatile data structures. It includes:
- **Lists Basics** – Creating and using lists
- **List Methods** – Common methods like `append()`, `remove()`, `sort()`, etc.
- **List Comprehension** – A concise way to create lists using loops and conditions

## 📁 13_tuples
This section introduces tuples, immutable sequences in Python. It includes:
- **Tuple Basics** – Creating and using tuples
- **Tuple Unpacking** – Assigning tuple elements to variables
- **Tuple Methods** – Common tuple operations and functions

## 📁 14_sets
This section explains sets, an unordered collection of unique elements. It includes:
- **Set Basics** – Creating and using sets
- **Set Methods** – Methods like `add()`, `remove()`, `union()`, `intersection()`, etc.
- **Set Operations** – Performing mathematical set operations

## 📁 15_dictionaries
This section covers dictionaries, Python’s key-value pair data structure. It includes:
- **Dictionary Basics** – Creating and using dictionaries
- **Dictionary Methods** – Common methods like `keys()`, `values()`, `items()`, `get()`, etc.
- **Dictionary Comprehension** – A concise way to create dictionaries

## 📁 16_oops
This section introduces Object-Oriented Programming (OOP) concepts in Python. It includes:
- **Classes** – Creating classes and objects
- **Constructors** – Using the `__init__` method
- **Instance vs Class Variables** – Difference between instance-level and class-level data
- **Inheritance** – Reusing code and extending classes
- **Operator Overloading** – Defining custom behavior for operators with special methods

## 📁 17_python_advanced_concepts
This section covers advanced Python concepts and features for writing more powerful programs. It includes:
- **Decorators** – Enhancing functions without modifying them
- **Decorators with Arguments** – Passing arguments to decorators
- **Getters and Setters** – Controlling access to class attributes
- **Instance, Static, and Class Methods** – Different method types in classes
- **Dunder (Magic) Methods** – Special methods like `__str__`, `__len__`, etc.
- **Errors & Exception Handling** – Handling errors gracefully
- **Else Clause** – Using `else` with loops and exceptions
- **Finally Clause** – Guaranteeing code execution after `try-except`
- **Map Function** – Applying a function to all items in an iterable
- **Filter Function** – Filtering elements based on a condition
- **Reduce Function** – Reducing an iterable to a single value
- **Walrus Operator** – Assignment expressions (`:=`)
- **Args (`*args`)** – Passing a variable number of positional arguments
- **Kwargs (`**kwargs`)** – Passing a variable number of keyword arguments
- **Combined Args and Kwargs** – Using `*args` and `**kwargs` together

## 📁 18_files
This section focuses on file handling and related operations in Python. It includes:
- **Reading Files** – Opening and reading file content (`01_read.py`)
- **Writing Files** – Writing content to files (`02_write.py`)
- **Appending Files** – Adding content without overwriting (`03_append.py`)
- **Line by Line Reading** – Iterating through file lines (`04_line_by_line.py`)
- **With Statement** – Managing files with context managers (`05_with.py`)
- **OS Module** – Interacting with the operating system (`06_os.py`)
- **Shutil Module** – High-level file operations (`07_shutil.py`)
- **Argparse Module** – Handling command-line arguments (`08_argparse.py`)
- **Sample Files** – Example text files (`john.txt`, `harry.txt`, `John Doe.txt`) for testing file operations

## 📄 README.md
You're reading it! This file provides an overview of the repository structure and a brief description of each section to help you navigate the content.

---

Feel free to clone the repo and explore the folders for a hands-on learning experience!
