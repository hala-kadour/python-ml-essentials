# Module 03: Python Functions & Classes

## Overview
This module explores Python functions, advanced functional tools, and Object-Oriented Programming (OOP) principles. Understanding how to structure logic, handle scope, reuse code via closures, and design robust classes is fundamental for writing scalable and maintainable applications.

## Covered Concepts

### 1. Functions Fundamentals (`01_functions_fundamentals.ipynb`)
The building blocks of modular Python code.
* **Function Definition:** Declaring reusable code blocks using `def` and handling `return` statements.
* **Docstrings & Documentation:** Writing clear inline documentation and inspecting function metadata using `__doc__` and `help()`.

### 2. Function Arguments and Closures (`02_function_arguments_and_closures.ipynb`)
Flexible parameter passing and retaining function state.
* **Positional & Keyword Arguments:** Working with explicit order, default values, and dynamic arguments (`*args` and `**kwargs`).
* **Nested Functions & Scope:** Managing variable scoping across nested functions using the `nonlocal` keyword.
* **Closures:** Creating inner functions that retain access to their enclosing scope variables across calls.

### 3. Advanced Functional Tools (`03_advanced_functional_tools.ipynb`)
Writing efficient, reusable, and data-driven functional pipelines.
* **Partial Functions:** Freezing function arguments to create simplified callable signatures using `functools.partial`.
* **Generators:** Evaluating sequences lazily using `yield` for memory-efficient data processing.
* **Decorators:** Extending or modifying existing function behavior cleanly without altering the source code.
* **Functional Data Application:** Mapping transformations across collections and Pandas DataFrames using `map()` and `.apply()`.

### 4. OOP Fundamentals (`04_oop_fundamentals.ipynb`)
Foundational concepts of Object-Oriented Programming.
* **Class Definition & Instantiation:** Creating custom classes as blueprints and instantiating concrete objects.
* **Constructor (`__init__`) & `self`:** Binding instance-specific attributes using `self`.
* **Instance vs. Class Variables:** Distinguishing between instance-specific data and shared class properties.
* **Instance Methods:** Implementing behavior that operates on instance state.

### 5. OOP Advanced Concepts (`05_oop_advanced_concepts.ipynb`)
Mastering inheritance, magic methods, and clean encapsulation.
* **Inheritance & `super()`:** Reusing parent class functionality (Single and Multiple Inheritance) and invoking base constructors.
* **Special Dunder Methods:** Customizing built-in behaviors using magic methods such as `__str__`, `__len__`, and `__call__`.
* **Encapsulation with `@property`:** Protecting sensitive instance attributes using read-only property getters.
* **Class & Static Methods:** Utilizing `@classmethod` for alternative constructors and `@staticmethod` for utility methods.

## Execution
Open the provided Jupyter Notebooks in order to interact directly with the code blocks:
1. `01_functions_fundamentals.ipynb`
2. `02_tuples_and_sets.ipynb` -> `02_function_arguments_and_closures.ipynb`
3. `03_advanced_functional_tools.ipynb`
4. `04_oop_fundamentals.ipynb`
5. `05_oop_advanced_concepts.ipynb`