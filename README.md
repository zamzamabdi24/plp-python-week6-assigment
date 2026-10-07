# Week 6 Assignment: Safe Functions

This assignment practices catching errors with `try` / `except`, naming the specific expected error, and keeping a program running instead of crashing.

## Files

- `safe_tools.py` — Contains the `safe_divide`, `safe_number`, and `get_field` functions and their test output.

## Why can the if check not catch abc on its own?

An `if` check cannot catch `"abc"` on its own because `"abc"` is valid text and does not cause an error by itself. The error only happens when Python tries to convert it using `int("abc")`, which raises a `ValueError`; therefore, `try` / `except ValueError` is needed.
