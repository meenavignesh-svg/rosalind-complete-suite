# INI2 - Variables and Some Arithmetic: Answer 1

## Question

This Python Village problem introduces variables and arithmetic expressions. Given two positive integers `a` and `b`, the task is to calculate the sum of their squares:

```text
a^2 + b^2
```

For this submitted answer, the provided Rosalind dataset values are:

```text
a = 856
b = 957
```

## Answer 1

```python
a = 856
b = 957
print((a ** 2) + (b ** 2))
```

## Output

```text
1648585
```

## Explanation

The program stores the two integer values in variables named `a` and `b`. Python's exponent operator `**` is used to square each value:

```python
a ** 2
b ** 2
```

Then the two squared values are added together. With `a = 856` and `b = 957`, the calculation is:

```text
856^2 + 957^2 = 732736 + 915849 = 1648585
```

The final result is printed to standard output.

## Complexity Analysis

| Metric | Complexity | Reason |
| --- | --- | --- |
| Time Complexity | O(1) | The program performs a fixed number of arithmetic operations. |
| Space Complexity | O(1) | The program stores only two integer variables and one computed result. |

## Edge Cases

For the Rosalind problem constraints, the input values are positive integers. The same approach also works for zero or negative integers because squaring removes the sign before addition.
