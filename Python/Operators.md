## Basic Operators

**Priority** | **Operator**
---|---
1 | **
2 | +, - (unary)
3 | \*, /, //, %
4 | +, -
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




