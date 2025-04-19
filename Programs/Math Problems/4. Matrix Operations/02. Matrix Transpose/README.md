# Matrix Transpose

## Problem Statement

Given a matrix A, find the transpose of A, denoted as $A^T$.
The transpose of a matrix is obtained by swapping its rows and columns.

## Input

- The first line contains two integers N and M, the number of rows and columns of the matrix.
- The next N lines contain M integers each, representing the elements of matrix A.
- The elements of the matrix are separated by spaces.
- The matrix is guaranteed to be rectangular, meaning N and M can be different.
- The elements of the matrix are integers and can be positive or negative.

## Output

- Print the transpose of the matrix A, denoted as $A^T$.
- The output should be formatted as a matrix with M rows and N columns.
- Each row of the transposed matrix should be printed on a new line.

## Example

### Input

```
3 2
1 2
3 4
5 6
```

### Output

```
1 3 5
2 4 6
```

### Input

```
4 3
1 2 3
4 5 6
7 8 9
10 11 12
```

### Output

```
1 4 7 10
2 5 8 11
3 6 9 12
```

## Constraints

- The number of rows N and columns M will be between 1 and 1000.
- The elements of the matrix will be between -1000 and 1000.
- The input will always be valid and follow the specified format.
