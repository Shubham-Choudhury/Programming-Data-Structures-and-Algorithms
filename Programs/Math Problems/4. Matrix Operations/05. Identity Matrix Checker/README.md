# Identity Matrix Checker

## Problem Statement

Given a square matrix, check if it is an identity matrix.
An identity matrix is a square matrix in which all the elements of the principal diagonal are ones and all other elements are zeros.

```
1 0 0 0
0 1 0 0
0 0 1 0
0 0 0 1
```

is an example of a 4x4 identity matrix.

## Input

- The first line contains an integer N, the size of the matrix.
- The next N lines contain N integers each, representing the elements of the matrix.
- The elements of the matrix are separated by spaces.
- The elements of the matrix are integers and can be positive or negative.
- The matrix is square, meaning it has the same number of rows and columns.

## Output

- If the matrix is an identity matrix, print "YES".
- If the matrix is not an identity matrix, print "NO".

## Example

### Input

```
3
1 0 0
0 1 0
0 0 1
```

### Output

```
YES
```

### Input

```
3
0 0 1
0 1 0
1 0 0
```

### Output

```
NO
```
