# Matrix Addition/Subtraction

## Problem Statement

Given two matrices A and B, perform matrix addition or subtraction based on the operator provided.

## Input

- The first line contains two integers N and M, the number of rows and columns of the matrices.
- The next N lines contain M integers each, representing the elements of matrix A.
- The next N lines contain M integers each, representing the elements of matrix B.
- The last line contains a character '+' or '-' indicating the operation to be performed.

## Output

- If the operator is '+', print the resulting matrix after addition.
- If the operator is '-', print the resulting matrix after subtraction.
- The output should be formatted as a matrix with N rows and M columns.

## Example

### Input

```
3 3
1 2 3
4 5 6
7 8 9

1 1 1
1 1 1
2 2 2
+
```

### Output

```
2 3 4
5 6 7
9 10 11
```

### Input

```
4 3
1 2 3
4 5 6
7 8 9
1 1 1

1 1 1
1 1 1
1 2 1
3 4 5
-
```

### Output

```
0 1 2
3 4 5
6 6 8
-2 -3 -4
```

## Constraints

- The number of rows N and columns M are between 1 and 100.
- The elements of the matrices are integers between -1000 and 1000.
- The operator will always be either '+' or '-'.
- The matrices will always have the same dimensions.
