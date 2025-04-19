# Solve System of 2 Linear Equations (2x2 matrix method)

## Problem Statement

Given a system of two linear equations in two variables, solve for the values of the variables using the 2x2 matrix method.
The equations are of the form:

- $a_1x + b_1y = c_1$
- $a_2x + b_2y = c_2$

Where:

- $a_1$, $b_1$, $c_1$, $a_2$, $b_2$, and $c_2$ are real numbers.
- The coefficients can be positive or negative real numbers.
- The system of equations has a unique solution (i.e., the lines intersect at a single point).

## Input

- The input consists of six real numbers $a_1$, $b_1$, $c_1$, $a_2$, $b_2$, and $c_2$.
- The coefficients can be positive or negative real numbers.

## Output

- Print the values of $x$ and $y$ in the following format:
  - "x = value, y = value"
- The values of $x$ and $y$ should be printed with 2 decimal places of precision.

## Example

### Input

```
1 2 3 4 5 6
```

### Output

```
x = 1.50, y = 1.00
```

### Input

```
2 3 4 5 6 7
```

### Output

```
x = 1.00, y = 1.50
```

## Explanation

- For the first input, the system of equations is:
  - $1x + 2y = 3$
  - $4x + 5y = 6$
- The solution is found using the 2x2 matrix method, resulting in $x = 1.50$ and $y = 1.00$.
- For the second input, the system of equations is:
  - $2x + 3y = 4$
  - $5x + 6y = 7$
- The solution is found using the 2x2 matrix method, resulting in $x = 1.00$ and $y = 1.50$.

## Constraints

- The coefficients $a_1$, $b_1$, $c_1$, $a_2$, $b_2$, and $c_2$ are real numbers.
- The coefficients can be positive or negative real numbers.
- The system of equations has a unique solution (i.e., the lines intersect at a single point).
