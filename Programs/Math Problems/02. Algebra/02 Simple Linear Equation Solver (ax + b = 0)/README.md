# Simple Linear Equation Solver `(ax + b = 0)`

## Problem Statement

Solve the linear equation `(ax + b = 0)` for `x`. The equation can be rearranged to find the value of `x` as follows:

$x = -\frac{b}{a}$

where `a` is not equal to `0`. If `a` is equal to `0`, the equation has no solution.
The solution is valid for all real numbers `a` and `b`.

## Input

- The input consists of two real numbers `a` and `b` separated by a space.
- The first number `a` is the coefficient of `x` and the second number `b` is the constant term.
- The input can be positive or negative real numbers.

## Output

- The output should be the value of `x` rounded to 2 decimal places.
- If `a` is equal to `0`, print "No solution".
- The output should be in the format: "x = value" where `value` is the calculated value of `x`.

## Example

### Input

```
2 -4
```

### Output

```
x = -2.00
```

### Input

```
0 5
```

### Output

```
No solution
```

## Explanation

- For the first input, the equation is `2x - 4 = 0`, which simplifies to `x = -2.00`.
- For the second input, since `a` is `0`, the equation has no solution, so the output is "No solution".

## Constraints

- The values of `a` and `b` can be any real numbers.
- The output should be formatted to 2 decimal places.
- The program should handle both positive and negative values of `a` and `b`.
- The program should also handle edge cases such as `a = 0` and `b = 0`.
