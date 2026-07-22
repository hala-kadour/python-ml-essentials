# Module 01: Python Fundamentals

## Overview
This module covers the core building blocks of Python programming. Understanding these fundamentals is critical before moving on to complex machine learning algorithms or data engineering pipelines. 

## Covered Concepts

### 1. Variables and Assignments (`variables-and-assignments.ipynb`)
Python is dynamically typed, meaning variable types are determined at runtime. 
* **Dynamic Assignment:** Assigning integers, floats, and strings without explicit type declarations.
* **String Formatting:** Utilizing `f-strings` for clean and readable variable interpolation within strings.
* **Reassignment:** Understanding how variables point to values and the implications of copying variables.

### 2. Working with Types (`working-with-types.ipynb`)
Exploring the primary data types required for standard data manipulation:
* **Strings (`str`):** Handling text using single, double, and triple quotes, and string concatenation.
* **Integers & Floats (`int`, `float`):** Performing numerical operations and understanding type changes during mathematical evaluations (e.g., division yielding a float).
* **Booleans (`bool`):** Working with `True` and `False`, and utilizing the `bool()` built-in function to evaluate "truthy" or "falsy" values (e.g., `1` vs `0`).
* **NoneType (`None`):** Representing null or missing values, which is especially useful in conditional logic or function returns.

### 3. Logic and Conditionals (`conditionals-and-evaluations.ipynb`)
Controlling the flow of execution based on specific conditions:
* **`if`, `elif`, and `else` Statements:** Building logic trees.
* **Truthy/Falsy Evaluations:** Using empty data structures (like `[]`) or the integer `0` as `False`, while populated lists or positive integers evaluate to `True`.
* **Logical Operators:** Compounding conditions using `and`, and negating evaluations using the `not` keyword.

### 4. Exceptions and Error Handling (`exceptions.ipynb`)
Writing robust code requires anticipating and handling potential failures without crashing the program.
* **Raising Errors:** Deliberately stopping execution using `raise` (e.g., `RuntimeError`).
* **Try/Except Blocks:** Catching specific exceptions like `ZeroDivisionError` rather than using bare `except Exception:` blocks, ensuring that unexpected errors are still properly flagged.
* **Capturing Exception Output:** Using `except Exception as error:` to log or print the exact cause of the failure.

## Execution
Open the provided Jupyter Notebooks to interact directly with the code blocks:
