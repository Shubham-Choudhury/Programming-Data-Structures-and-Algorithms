# Matrix-Based System Solver (Gauss Elimination)

## Problem Statement

Solve a system of linear equations using the Gauss elimination method. The system of equations can be represented in matrix form as:
$$Ax = b$$
where:

- $A$ is the coefficient matrix.
- $x$ is the vector of variables.
- $b$ is the constant vector.
  The goal is to find the vector $x$ that satisfies the equation.

## Gauss Elimination

The Gauss elimination method consists of two main steps:

1. Forward elimination: Transform the matrix $A$ into an upper triangular form.
2. Back substitution: Solve for the variables starting from the last equation and substituting back into the previous equations.

## Input

- The first line contains an integer $n$, the number of equations (and variables).
- The next $n$ lines each contain $n+1$ space-separated real numbers representing the coefficients of the equations and the constants. The first $n$ numbers in each line represent the coefficients of the variables, and the last number represents the constant term.
- The coefficients can be positive or negative real numbers.
- The system of equations is guaranteed to have a unique solution.

## Output

- Print the solution vector $x$ in the following format:
  - "x1 = value1, x2 = value2, ..., xn = valueN"
- The values should be printed with 2 decimal places of precision.

## Example

### Input

```
3
2 1 -1 8
1 -1 2 3
-1 2 3 4
```

### Output

```
x1 = 2.00, x2 = 1.00, x3 = 3.00
```

### Input

```
4
4 2 -1 1 8
1 -1 2 3 4
1 2 5 -1 5
1 1 2 3 6
```

### Output

```
x1 = 1.00, x2 = 2.00, x3 = 3.00, x4 = 4.00
```

## Constraints

- The number of equations $n$ is a positive integer.
- The coefficients and constants are real numbers.
- The system of equations is guaranteed to have a unique solution.
- The input values can be positive or negative real numbers.
- The output values should be rounded to 2 decimal places.
