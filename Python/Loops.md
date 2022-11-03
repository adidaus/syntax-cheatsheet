## While
```python
while conditional_expression:
	instruction

else:  # rarely used
	instruction  # always executed once
```

## For
```python
for i in range(100):
	# do_something()
	pass  # empty instruction, does nothing

else:  # rarely used
	instruction  # always executed once
```



### syntactic candy/sugar
keywords:
-   `break` - exits the loop immediately, and unconditionally ends the loop's operation; the program begins to execute the nearest instruction after the loop's body;
-   `continue` - behaves as if the program has suddenly reached the end of the body; the next turn is started and the condition expression is tested immediately.