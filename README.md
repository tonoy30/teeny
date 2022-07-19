# teeny transpiler
This is a small transpiler to demonstrate how compilers work. It compiles our own dialect to C, while being written in Python.

It supports:

* Numerical variables
* Basic arithmetic
* If statements
* While loops
* Print text and numbers
* Input numbers
* Labels and goto
* Comments

```
# Compute average of given values.

LET a = 0
WHILE a < 1 REPEAT
    PRINT "Enter number of scores: "
    INPUT a
ENDWHILE

LET b = 0
LET s = 0
PRINT "Enter one value at a time: "
WHILE b < a REPEAT
    INPUT c
    LET s = s + c
    LET b = b + 1
ENDWHILE

PRINT "Average: "
PRINT s / a
```
