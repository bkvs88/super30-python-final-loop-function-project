# super30-python-final-loop-function-project
Final Combined Challenge: Loops + While + Functions

## Project Objective

This directory contains a collection of **twelve mini Python applications** built to reinforce core Python programming concepts such as functions, loops, conditionals, dictionaries, lists, and validation. Each program solves a practical, real-world style problem (banking, shopping, student management, authentication, etc.) and demonstrates how to structure a complete, menu-driven or function-based application.

The main learning goals are:

- Build reusable functions that accept inputs and return meaningful results.
- Use `while` and `for` loops to run interactive menus and process collections.
- Apply conditionals and validation to handle correct and incorrect user input.
- Work with built-in data structures (dictionaries, lists, tuples, sets).
- Combine multiple concepts into cohesive, user-facing applications.
- Provide clear input/output flow and error handling.

---

## Programs Completed

| # | File | Description |
|---|------|-------------|
| 1 | `bank_application.ipynb` | Menu-driven banking app to check balance, deposit, withdraw, and view transaction history. |
| 2 | `employee_sal_analyzer.ipynb` | Analyzes employee salaries to compute total payroll, average, highest, lowest, and employees above average. |
| 3 | `expense_tracker.ipynb` | Lets a user repeatedly add expenses and view them, calculate the total, and find the highest expense. |
| 4 | `inventory_management.ipynb` | Maintains products (name, price, quantity) with functions to add, display, search, update quantity, and total value. |
| 5 | `mini_authentication_system.ipynb` | Small login system with predefined username/password, max attempts, success/failure handling, logout, and retry logic. |
| 6 | `number_analysis_tool.ipynb` | Analyzes a list of numbers (largest, smallest, total, average, even/odd and positive/negative counts) without using `min()`, `max()`, or `sum()`. |
| 7 | `password_strength_checker.ipynb` | Checks a password for uppercase, lowercase, number, special character, and minimum length; returns a strength result. |
| 8 | `prime_number_analyzer.ipynb` | Finds prime numbers within a range, counts them, sums them, and displays the largest prime found. |
| 9 | `quiz_application.ipynb` | Asks at least 5 Python questions one at a time, checks answers, tracks score, and shows final percentage. |
| 10 | `shopping_cart.ipynb` | Simple cart that lets users add/remove products, view the cart, calculate the bill, and exit. |
| 11 | `student_management_system.ipynb` | Collects student marks, computes total, percentage, grade, and pass/fail result with validation. |
| 12 | `super30_utility.ipynb` | Menu-driven "Super30" utility app with at least five tools (calculator, palindrome checker, prime checker, word counter, temperature converter, etc.). |

---

## How to Execute the Programs

Each program is a **Jupyter Notebook** (`.ipynb`). There are two ways to run them:

### 1. Via Jupyter (Recommended)

Open a terminal in this directory and launch Jupyter:

```bash
jupyter notebook
```

or with VS Code:

```bash
code Loops_7/
```

Then open any notebook (e.g. `bank_application.ipynb`) and run all cells with **Cell → Run All** (Shift+Enter runs an individual cell).

### 2. Convert to a Python script and run

Convert any notebook to a `.py` file and execute it:

```bash
jupyter nbconvert --to script bank_application.ipynb
python bank_application.py
```

> **Note:** Programs that use `input()` (bank, expense tracker, quiz, shopping cart, authentication, etc.) expect interactive terminal input, so run them in a terminal or interactive environment rather than as a non-interactive script.

---

## Concepts Used

- **Functions** — defining reusable blocks (`def`, parameters, return values, docstrings).
- **Loops** — `while` for menu-driven programs and retries; `for` for iterating over lists/dictionaries/ranges.
- **Conditionals** — `if`/`elif`/`else` for decision making and validation.
- **Data Structures** — dictionaries (`{}`), lists (`[]`), and tuples.
- **Input/Output** — `input()`, `print()`, and formatted output (f-strings, `:.2f`).
- **Error Handling** — `try`/`except` and raising `ValueError` for invalid input.
- **Strings & Operations** — string methods for password checking, palindromes, and word counting.
- **Modular Design** — reusable functions and menu/utility structuring.
