# Matrix Multiplication

## Problem Statement

Given two matrices A and B, perform matrix multiplication to obtain the product matrix C = AB.
The product of two matrices is defined only when the number of columns in the first matrix is equal to the number of rows in the second matrix.

## Input

- The first line contains two integers N and M, the number of rows and columns of matrix A.
- The second line contains two integers P and Q, the number of rows and columns of matrix B.
- The next N lines contain M integers each, representing the elements of matrix A.
- The next P lines contain Q integers each, representing the elements of matrix B.
- The elements of the matrices are separated by spaces.
- The elements of the matrices are integers and can be positive or negative.

## Output

- Print the product matrix C, which will have dimensions N x Q.
- Each row of the product matrix should be printed on a new line.
- Each element in the row should be separated by a space.
- If the matrices cannot be multiplied (i.e., M != P), print "Matrix multiplication not possible".

## Example

### Input

```
2 3
3 2

1 2 3
4 5 6

10 11
20 21
30 31
```

### Output

```
140 146
320 335
```

## Constraints

- The number of rows N and P will be between 1 and 1000.
- The number of columns M and Q will be between 1 and 1000.
- The elements of the matrices will be integers and can be positive or negative.
- The number of columns in matrix A (M) must be equal to the number of rows in matrix B (P) for multiplication to be valid.
- The product matrix C will have dimensions N x Q.
- The output should be formatted as a matrix with N rows and Q columns.
