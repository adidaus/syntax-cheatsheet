# Variables

## Javascript

Javascript has several ways to declare a variable using “let” or “const”, depending on whether the variable needs to be updated in the future (“var” can also be used, but it’s an outdated way of declaring variables).

```js
let x = "Hello there"  
const y = "Good bye"
```

## Python

```python
x = "Hello there"  
y = "Good bye"
```

First, you should know that Python doesn’t have a dedicated syntax for defining constants.

To tell other programmers that a given value should be _treated as a constant_, you must use a widely accepted naming convention for the constant’s identifier or name. You should write the name in capital letters with underscores separating words, as stated in the [Constants](https://peps.python.org/pep-0008/#constants) section of [PEP 8](https://realpython.com/python-pep8/).

```python
PI = 3.14
MAX_SPEED = 300
```


# Arithmetic Operators

The arithmetic operators between Javascript and Python are identical — except for one. Python is missing the pre-decrement/ post-decrement, and pre-increment/ post-increment operators.

## Javascript extra operators:
#### Postfix Increment/Decrement

```js
let x = 3;
const y = x++;

// x = 4
// y = 3
```

#### Prefix Increment/Decrement
```js
let x = 3;
const y = --x;

// x = 2
// y = 2
```

## Python extra operator:

One thing to note- since Python treats all numbers as floats (decimal numbers), you can use the double division sign // to get an integer. This is useful for finding indexes.

```python
string1 = "abcde"  middle = string1[len(string1) // 2]   
print(middle) # c
```
