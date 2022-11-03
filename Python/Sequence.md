**Lists, tuples, and strings are sequences** because things come out of them in the same order they were put in. Sets and dictionaries are collections.

## Lists
The **list is a type of data** in Python used to **store multiple objects**. It is an **ordered and mutable collection**
```python
[1, 2, 3]
```

Removing Elements and Delete List
```python
del numbers[1]
del my_list[1:3]
del my_list[:]  # empty list
del my_list     # delete the list itself
```

Iterate trough using `for` loop
```python
for i in my_list:
	print(i)
```
or using range()
```python
for i in range(len(my_list))
	print(my_list[i])
```

The `in` and `not in` operators
Python offers two very powerful operators, able to **look through the list in order to check whether a specific value is stored inside the list or not**.
```python
elem in my_list
elem not in my_list
```

### List Methods
#### .append(value)
#### .insert(location, value)
#### .sort()
#### .reverse()


Lists (and many other complex Python entities) are stored in different ways than ordinary (scalar) variables.

You could say that:

-   the name of an ordinary variable is the **name of its content**;
-   the name of a list is the name of a **memory location where the list is stored**.

The assignment: `list_2 = list_1` copies the name of the array, not its contents. In effect, the two names (`list_1` and `list_2`) identify the same location in the computer memory. Modifying one of them affects the other, and vice versa.

### Slice
A slice is an element of Python syntax that allows you to **make a brand new copy of a list, or parts of a list**.

```python
my_list[start:end]
```
A slice of this form **makes a new (target) list, taking elements from the source list - the elements of the indices from start to `end - 1`**.






