# Inverse of Matrix (Gauss-Jordan Elimination)

## Problem Statement

We are given a matrix $A$ of size $N \times N$ and we need to find its inverse using Gauss-Jordan elimination method. The inverse of a matrix $A$ is denoted as $A^{-1}$ and it satisfies the equation $A \cdot A^{-1} = I$, where $I$ is the identity matrix.

## Input

The input consists of $N$ lines, each representing a row of the matrix $A$. Each row contains $N$ integers separated by spaces. The elements of the matrix can be positive or negative integers.

## Output

The output should be the inverse of the matrix $A$ rounded to 2 decimal places. If the matrix is not invertible, output "Matrix is not invertible". The output should be formatted as a matrix, with each row on a new line and elements separated by spaces.

## Example

### Input

```
3
1 2 3
2 4 5
3 5 6
```

### Output

```
1 -3 2
-3 3 -1
2 -1 0
```
