# LU Decomposition

## Program Statement

We are given a matrix $A$ of size $N \times N$ and we need to find its LU decomposition. The LU decomposition of a matrix $A$ is a factorization of the form $A = LU$, where $L$ is a lower triangular matrix and $U$ is an upper triangular matrix.

## Input

The input consists of $N$ lines, each representing a row of the matrix $A$. Each row contains $N$ integers separated by spaces. The elements of the matrix can be positive or negative integers.

## Output

The output should be the matrices $L$ and $U$ rounded to 2 decimal places. The output should be formatted as two matrices, with each row on a new line and elements separated by spaces.

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
1 0 0
3 1 0
2 0 1

1 2 3
0 -1 -3
0 0 -1
```
