# Week1-Assignment1
End-to-end Python exploratory data analysis and data processing project covering data cleaning, statistical analysis, and visual data insights.
# DA & DS Week 1 Assignment

## Python & NumPy Fundamentals

This repository contains my Week 1 assignment for **Data Analytics & Data Science (DA & DS)**. The assignment covers the fundamentals of Python programming and basic NumPy concepts.

## Assignment Overview

The assignment focuses on understanding basic Python concepts and applying them through simple examples and programs.

### Topics Covered

1. Introduction to Python
2. Features of Python
3. Mutable and Immutable Data Types
4. List and Tuple
5. Python Operators
6. Conditional Statements
7. Functions
8. For Loop and While Loop
9. Introduction to NumPy
10. Slicing in Python Lists and NumPy Arrays
11. `range()` Function
12. Palindrome Logic

## File Structure

```text
DA_DS_Week1_Assignment/
│
├── DA_DS_Week1_Assignment.ipynb
└── README.md
```

## Description of the Assignment

### 1. Introduction to Python

Python is a high-level, interpreted programming language known for its simple and readable syntax. It is widely used in data science, data analytics, machine learning, web development, and automation.

Some important features of Python are:

* Easy and readable syntax
* Platform independent
* Large collection of libraries
* Open-source and freely available

### 2. Mutable and Immutable Data Types

Mutable data types can be modified after they are created. For example, lists are mutable.

Immutable data types cannot be changed after they are created. Examples include tuples and strings.

### 3. List and Tuple

A list is a mutable collection that uses square brackets `[]`.

Example:

```python
numbers = [1, 2, 3]
```

A tuple is an immutable collection that uses parentheses `()`.

Example:

```python
numbers = (1, 2, 3)
```

### 4. Operators

Operators are symbols used to perform operations on values and variables.

The assignment covers:

* Arithmetic operators
* Comparison operators
* Logical operators
* Assignment operators

Example:

```python
print(10 + 5)
print(10 > 5)
print(10 > 5 and 8 > 3)
x = 10
```

### 5. Conditional Statements

Conditional statements are used to make decisions in a program based on specified conditions.

The assignment demonstrates the use of:

* `if`
* `elif`
* `else`

Example:

```python
if condition:
    statement
elif condition:
    statement
else:
    statement
```

### 6. Functions

A function is a block of reusable code designed to perform a specific task.

Advantages of functions include:

* Reducing code repetition
* Improving readability
* Making debugging easier
* Supporting code reuse

### 7. Loops

Loops are used to execute a block of code repeatedly.

The assignment explains the difference between:

* `for` loop
* `while` loop

A `for` loop is generally used when the number of iterations is known, while a `while` loop is useful when repetition depends on a condition.

### 8. NumPy

NumPy is a Python library used for numerical and mathematical operations.

NumPy is preferred over Python lists for many numerical tasks because it:

* Provides faster numerical calculations
* Uses memory efficiently
* Supports mathematical operations easily
* Works effectively with large datasets

### 9. Slicing

Slicing is used to access a specific portion of a sequence such as a list or NumPy array.

Python list example:

```python
numbers = [1, 2, 3, 4, 5]
print(numbers[1:4])
```

NumPy array example:

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])
print(arr[1:4])
```

### 10. `range()` Function

The `range()` function generates a sequence of numbers.

It can have three parameters:

```text
range(start, stop, step)
```

Example:

```python
for i in range(1, 10, 2):
    print(i)
```

### 11. Palindrome Logic

A palindrome is a word, number, or string that reads the same forward and backward.

Examples include:

* `madam`
* `level`
* `121`

The basic logic is to compare the original value with its reversed value.

## Requirements

To run the notebook, the following are required:

* Python 3.x
* Jupyter Notebook or Google Colab
* NumPy library

NumPy can be installed using:

```bash
pip install numpy
```
## Learning Outcomes

After completing this assignment, I gained an understanding of:

* Basic Python programming concepts
* Python data types
* Lists and tuples
* Operators
* Conditional statements
* Functions
* Loops
* NumPy basics
* Slicing
* The `range()` function
* Basic palindrome logic

## Conclusion

This assignment provides a foundation in Python and NumPy, which are important tools for data analytics and data science. The concepts covered in this assignment will be useful for working with data, performing numerical operations, and developing data science programs.
