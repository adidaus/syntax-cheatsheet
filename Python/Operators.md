## Basic Operators

**Priority** | **Operator**
---|---
1 | **
2 | +, - (unary)
3 | \*, /, //, %
4 | +, - (binary)
5 | <, <=, >, >=
6 | ==, !=

Both operators (`*` and `%`) have the same priority, so the result is detemined by the binding direction.

### Exponentiation
```python
2 ** 3    # 8
2 ** 3.   # 8.0
2. ** 3   # 8.0
2. ** 3.  # 8.0
2 ** 2 ** 3  # 256
```
**the exponentiation operator uses right-sided binding**.

## Division
```python
6 / 3    # 2.0
6 / 3.   # 2.0
6. / 3   # 2.0
6. / 3.  # 2.0
```
**The result produced by the division operator is always a float**

### Integer division
```python
6 // 4    # 1
6 // 4.   # 1.0
6. // 4   # 1.0
6. // 4.  # 1.0
-6 // 4   # -2
6. // -4  # -2.0
```
**rounding always goes to the lesser integer**.

## Remainder/Modulo
```python
14 % 4    # 2
12 % 4.5  # 3.0
```



**Remember**: Data and operators when connected together form **expressions**. The simplest expression is a literal itself.

## Logic Operators
and, or, not

## Bitwise Operators
manipulate single bits of data

-   `&` does a _bitwise and_, e.g., `x & y = 0`, which is `0000 0000` in binary,
-   `|` does a _bitwise or_, e.g., `x | y = 31`, which is `0001 1111` in binary,
-   `˜`  does a _bitwise not_, e.g., `˜ x = 240`*, which is `1111 0000` in binary,
-   `^` does a _bitwise xor_, e.g., `x ^ y = 31`, which is `0001 1111` in binary,
-   `>>` does a _bitwise right shift_, e.g., `y >> 1 = 8`, which is `0000 1000` in binary,
-   `<<` does a _bitwise left shift_, e.g., `y << 3 =` , which is `1000 0000` in binary




