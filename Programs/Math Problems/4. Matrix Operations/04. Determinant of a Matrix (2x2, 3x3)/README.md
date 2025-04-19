# Determinant of a Matrix (2x2, 3x3)

## Problem Statement
Compute the determinant of a 2x2 matrix and a 3x3 matrix.
The determinant is a scalar value that can be computed from the elements of a square matrix. It is denoted as $\text{det}(A)$ or $|A|$.
The determinant of a matrix is a useful value in linear algebra, particularly in solving systems of linear equations, finding the inverse of a matrix, and determining the volume of geometric shapes.

## Input
- The first line contains an integer N, the size of the matrix (2 or 3).
- The next N lines contain N integers each, representing the elements of the matrix.
- The elements of the matrix are separated by spaces.
- The elements of the matrix are integers and can be positive or negative.
- The matrix is square, meaning it has the same number of rows and columns.

## Output
- Print the determinant of the matrix.
- The determinant is a single integer value.

## Example
### Input
```
3
1 -3 2
4 -1 2
3  5 2
```
### Output
```
40
```
### Input
```
2
2 3
4 6
```
### Output
```
0
```

## Constraints
- The size of the matrix N will be either 2 or 3.
- The elements of the matrix will be integers and can be positive or negative.
