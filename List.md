Sequence: List

## List Comprehension
A list comprehension is actually a list, but **created on-the-fly during program execution, and is not described statically**.

Take a look at the snippet:

`   row = [WHITE_PAWN for i in range(8)]       `  

The part of the code placed inside the brackets specifies:

-   the data to be used to fill the list (`WHITE_PAWN`)
-   the clause specifying how many times the data occurs inside the list (`for i in range(8)`)

```python
squares = [x ** 2 for x in range(10)]
# [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
twos = [2 ** i for i in range(8)]
# [1, 2, 4, 8, 16, 32, 64, 128]
odds = [x for x in squares if x % 2 != 0]
# [1, 9, 25, 49, 81]
```

## Lists in lists: two-dimensional arrays
```python
board = []

for i in range(8):
	row = [EMPTY for i in range(8)]
	board.append(row)

# using list comprehension
board = [[EMPTY for i in range(8)] for j in range(8)]
```