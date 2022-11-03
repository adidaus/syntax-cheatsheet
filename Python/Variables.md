Python is a **dynamically-typed** language, which means you don't need to _declare_ variables in it.

**A variable comes into existence as a result of assigning a value to it**. Unlike in other languages, you don't need to declare it in any special way.

The [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) recommends the following naming convention for variables and functions in Python:

-   variable names should be lowercase, with words separated by underscores to improve readability (e.g., `var`, `my_variable`)
-   function names follow the same convention as variable names (e.g., `fun`, `my_function`)
-   it's also possible to use mixed case (e.g., `myVariable`), but only in contexts where that's already the prevailing style, to retain backwards compatibility with the adopted convention.

Swap Variables
```python
var_1, var_2 = var_2, var_1
```
