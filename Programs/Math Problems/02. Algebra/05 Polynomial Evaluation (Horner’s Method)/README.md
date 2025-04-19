# Polynomial Evaluation (Horner’s Method)

## Problem Statement

Given a polynomial $P(x) = a_nx^n + a_{n-1}x^{n-1} + \ldots + a_1x + a_0$, evaluate the polynomial at a given value of $x$ using Horner's method. This method is efficient and reduces the number of multiplications and additions required to evaluate the polynomial.

## Horner's Method

Horner's method rewrites the polynomial in a nested form:
$$P(x) = (((a_nx + a_{n-1})x + a_{n-2})x + \ldots + a_1)x + a_0$$
This form allows us to evaluate the polynomial using a single loop, making it computationally efficient.

## Input

- The first line contains an integer $n$ (1 ≤ n ≤ 1000), the degree of the polynomial.
- The second line contains $n + 1$ integers $a_0, a_1, \ldots, a_n$ (−1000 ≤ $a_i$ ≤ 1000), the coefficients of the polynomial.
- The third line contains a real number $x$ (−1000 ≤ $x$ ≤ 1000), the point at which the polynomial should be evaluated.

## Output

- Print the value of the polynomial $P(x)$ rounded to 2 decimal places.
- The output should be in the format "P(x) = value", where "value" is the evaluated result.

## Example

### Input

```
3
1 0 -2 1
2.5
```

### Output

```
P(2.5) = 1.00
```

### Input

```
5
1 0 0 0 0 1
1.2
```

### Output

```
P(1.2) = 1.00
```

## Constraints

- The degree of the polynomial $n$ is a positive integer.
- The coefficients $a_i$ are integers within the specified range.
- The value of $x$ is a real number within the specified range.
