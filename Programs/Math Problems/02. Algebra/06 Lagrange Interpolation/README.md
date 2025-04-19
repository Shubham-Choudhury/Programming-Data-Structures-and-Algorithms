# Lagrange Interpolation

## Problem Statement

Given a set of data points $(x_i, y_i)$, find the polynomial $p(x)$ of degree at most $n-1$ that passes through all the points, where $n$ is the number of data points. The polynomial can be expressed as:
$$p(x) = \sum_{i=0}^{n-1} y_i L_i(x)$$
where $L_i(x)$ is the Lagrange basis polynomial defined as:
$$L_i(x) = \prod_{j=0, j \neq i}^{n-1} \frac{x - x_j}{x_i - x_j}$$
The goal is to compute the coefficients $y_i$ and the Lagrange basis polynomials $L_i(x)$ for the given data points.

## Input

- A list of tuples representing the data points $(x_i, y_i)$ where $x_i$ and $y_i$ are real numbers.
- The list should contain at least two points to form a polynomial.
- The $x_i$ values should be distinct to avoid division by zero in the Lagrange basis polynomial calculation.
- The input can be provided as a list of tuples or a list of lists.
- The input can be provided in any order, and the function should handle it correctly.

## Output

- A list of coefficients representing the polynomial $p(x)$ in descending order of degree.
- The coefficients should be rounded to 2 decimal places.

## Example

### Input

```
[(1, 2), (2, 3), (3, 5)]
```

### Output

```
[1.0, 0.0, 0.0]
```

### Input

```
[(0, 1), (1, 2), (2, 0)]
```

### Output

```
[-1.0, 3.0, 1.0]
```

### Input

```
[(1, 1), (2, 4), (3, 9)]
```

### Output

```
[1.0, 0.0, 0.0]
```

## Explanation

- For the first input, the polynomial that passes through the points (1, 2), (2, 3), and (3, 5) is $p(x) = 1.0x^2 + 0.0x + 0.0$.
- For the second input, the polynomial that passes through the points (0, 1), (1, 2), and (2, 0) is $p(x) = -1.0x^2 + 3.0x + 1.0$.
- For the third input, the polynomial that passes through the points (1, 1), (2, 4), and (3, 9) is $p(x) = 1.0x^2 + 0.0x + 0.0$.
- The coefficients are rounded to 2 decimal places for clarity.
