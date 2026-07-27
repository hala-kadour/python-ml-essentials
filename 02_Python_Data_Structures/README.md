# Module 02: Python Data Structures

## Overview
This module explores Python's built-in data structures and iteration techniques. Choosing the correct structure for managing, querying, and transforming data is essential for writing clean, efficient, and maintainable Python code.

## Covered Concepts

### 1. Lists Fundamentals (`01_lists_fundamentals.ipynb`)
Lists are ordered, mutable sequences designed to hold collections of items.
* **Indexing & Slicing:** Accessing elements using zero-based indices, negative indexing, and extracting subsets using slice boundaries (`list[start:stop]`).
* **Adding Data:** Extending lists dynamically using `append()`, `insert()`, and `extend()`.
* **Removing Data:** Extracting and removing elements safely using `pop()` and `remove()`.

### 2. Tuples and Sets (`02_tuples_and_sets.ipynb`)
Understanding when to enforce immutability or uniqueness in data collections.
* **Tuples (`tuple`):** Immutable, read-only sequences used for protecting data integrity and variable unpacking.
* **Sets (`set`):** Unordered collections that guarantee unique values, enabling fast membership testing (`in`) and duplicate removal.

### 3. Dictionary Basics (`03_dictionary_basics.ipynb`)
Dictionaries allow fast key-value data lookups and mapping.
* **Creation & Manipulation:** Constructing dictionaries via literal syntax `{}` or the `dict()` constructor, and adding/updating keys.
* **Safe Retrieval:** Preventing unexpected `KeyError` crashes using `try/except` blocks or fallback methods like `.get()`.
* **Safe Removal:** Popping key-value pairs safely with default fallback values.

### 4. Advanced Iterations and Comprehensions (`04_advanced_iterations_and_comprehensions.ipynb`)
Writing concise and pythonic code for looping and data transformation.
* **Dictionary Iteration:** Looping over keys, values, and pairs using `.items()`.
* **Iteration Utilities:** Combining iterables with `zip()` and tracking loop indices with `enumerate()`.
* **Comprehensions:** Constructing filtered and transformed lists and dictionaries concisely using List and Dictionary Comprehensions.

## Execution
Open the provided Jupyter Notebooks in order to interact directly with the code blocks:
1. `01_lists_fundamentals.ipynb`
2. `02_tuples_and_sets.ipynb`
3. `03_dictionary_basics.ipynb`
4. `04_advanced_iterations_and_comprehensions.ipynb`