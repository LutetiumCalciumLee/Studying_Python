# Python

## 1. Programs and Programming Languages

- Program: A collection of sequential instructions written to be executed by a computer
- Programming: The process of creating programs using a programming language
- Programming Language: A language used to instruct a computer to perform tasks  
    - Low-level language (machine-oriented), high-level language (human-oriented)

## 2. Introduction to Python and Its Features

- Interpreter language: Executes commands line by line
- Dynamically typed language: Variable types are determined at runtime
- Platform-independent language: Runs on various operating systems

## 3. Python Practice Environment

- Google Colab: Web-based Python practice environment, free GPU provided, Chrome browser recommended

## 4. Basic Python Syntax

### 4.1 Keywords

- Predefined reserved words in Python  
  Examples: `False`, `None`, `True`, `and`, `as`, `assert`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`, `nonlocal`, `not`, `or`, `pass`, `raise`, `return`, `try`, `while`, `with`, `yield`

### 4.2 Identifier Rules

- Can use letters, numbers, and underscores (_) (cannot start with a number)
- Case sensitive
- Reserved words cannot be used
- Special characters are not allowed

### 4.3 Statements

- It is recommended to write one statement per line
- Multiple statements on one line can be separated by semicolons (;)
- Multi-line statements: use backslash (\$$ or parentheses

### 4.4 Indentation and Comments

- Code blocks are defined by indentation (typically 4 spaces)
- Single-line comment: `#`
- Multi-line comment: `'''`, `"""`

### 4.5 Docstrings

- Strings used to describe functions, classes, and modules
- Accessed via the `__doc__` attribute

## 5. Variables, Constants, and Literals

### 5.1 Variables

- Storage for values, no type declaration needed, use assignment operator (=)

### 5.2 Constants

- Written in uppercase and `_`, but reassignment is not prevented

### 5.3 Literals

- Values written directly in code (numbers, strings, booleans, etc.)

### 5.4 Special Literals & Literal Collections

- Special literals: `None`, `True`, `False`
- Collection literals: list, tuple, dictionary, set

## 6. Python Data Types

| Type       | Characteristics                       |
| :--        | :--                                   |
| Number     | Integer, float, complex               |
| List       | Ordered, mutable, allows duplicates   |
| Tuple      | Ordered, immutable, allows duplicates |
| String     | Sequence of characters, immutable     |
| Set        | Unordered, mutable, no duplicates     |
| Dictionary | Key-value pairs, ordered, mutable     |

- Everything is an object; data types are classes, variables are instances

## 7. Type Conversion and Casting

- Implicit conversion: Python interpreter automatically converts types
- Explicit conversion: Use functions like `int()`, `float()`, `str()`, etc.

## 8. Input, Output, and Import

- Output: `print()`
- Input: `input()`
- Importing modules: `import`, `from ... import ...`, use `as` for alias

## 9. Python Operators

| Type      | Example Operators          | Description                    |
| :--       | :--                       | :--                            |
| Arithmetic| +, -, *, /, //, %, **     | Basic mathematical operations  |
| Comparison| ==, !=, >, =, >       | Bit-level operations           |
| Membership| in, not in                | Sequence membership check      |
| Identity  | is, is not                | Object identity comparison     |

## 10. Control Flow

- Conditional statements: `if`, `elif`, `else`, can be nested
- Loops: `for`, `while`, `break`, `continue`, `pass`
- `range()`: generates a sequence of numbers

## 11. Functions

- Defining functions: `def`
- Arguments: default values, keyword, variable-length (`*args`, `**kwargs`)
- Return: `return`
- Recursive functions, lambda functions (`lambda`)
- Variable scope: global, local, nonlocal

## 12. Modules and Packages

- Module: A file containing functions, variables, classes, etc.
- Package: A folder containing multiple modules

## 13. File Input/Output

- Opening/closing files: `open()`, `close()`
- Reading/writing: `read()`, `write()`, `readline()`, `readlines()`
- Using the `with` statement is recommended

## 14. Exception Handling

- Exception types: SyntaxError, ZeroDivisionError, IndexError, KeyError, etc.
- Exception handling syntax: `try`, `except`, `else`, `finally`, `raise`
- User-defined exception classes possible

## 15. Object-Oriented Programming (OOP)

- Defining classes: `class`
- Object (instance): a concrete entity of a class
- Attributes (variables) and methods (functions)
- Inheritance, polymorphism, encapsulation, overloading/overriding
