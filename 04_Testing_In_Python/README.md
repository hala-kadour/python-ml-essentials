# Module 04: Testing in Python

## Overview
Testing helps you confirm that your code behaves as expected, while debugging helps you understand why it does not. Together, these practices make it much easier to change code safely, catch regressions early, and trust the results of a data or machine learning workflow.

This module uses only Python's standard library, so the examples run without installing additional packages.

## Covered Concepts

### 1. Assertions (`01_assertions.ipynb`)
Assertions are lightweight checks that document assumptions directly in code.
* **Basic Syntax:** Writing `assert` statements with clear, useful error messages.
* **Internal Assumptions:** Validating conditions that must hold for a function to be correct.
* **Assertions vs. Exceptions:** Using explicit exceptions for user input and business rules, and understanding why assertions can be disabled with Python's `-O` flag.

### 2. Unit Testing with `unittest` (`02_unit_testing.ipynb`)
Unit tests verify small pieces of code in isolation and make failures repeatable.
* **Test Cases:** Creating `unittest.TestCase` classes and test methods.
* **Common Assertions:** Using methods such as `assertEqual()`, `assertAlmostEqual()`, and `assertRaises()`.
* **Shared Setup:** Reusing consistent fixtures with `setUp()`.
* **Expected Errors:** Confirming that invalid input raises the intended exception.

### 3. Debugging Patterns (`03_debugging_patterns.ipynb`)
Debugging is easier when you approach it as a repeatable process rather than guesswork.
* **Tracebacks:** Reading the exception type, call path, and failing line.
* **Targeted Logging:** Inspecting inputs and intermediate values with the `logging` module.
* **Interactive Debugging:** Using `breakpoint()` and common `pdb` commands.
* **Debugging Workflow:** Reproducing, inspecting, isolating, fixing, and verifying a defect.

## Execution
Open the provided Jupyter Notebooks in order to interact directly with the code blocks:
1. `01_assertions.ipynb`
2. `02_unit_testing.ipynb`
3. `03_debugging_patterns.ipynb`
