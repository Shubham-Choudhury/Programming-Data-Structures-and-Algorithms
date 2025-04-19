# Matrix Exponentiation (for Fibonacci, Recurrences)

## Problem Statement

Given a matrix $A$ and an integer $n$, compute the matrix $A^n$ (matrix raised to the power of n). This is useful for solving problems related to Fibonacci numbers and other recurrences.

## Input

- The first line contains an integer $N$, the size of the matrix.
- The next $N$ lines contain $N$ integers each, representing the elements of the matrix.
- The elements of the matrix are separated by spaces.
- The elements of the matrix are integers and can be positive or negative.
- The last line contains an integer $k$, the power to which the matrix should be raised.

## Output

- The output should be the resulting matrix after raising it to the power of $k$.
- The output should be formatted as a matrix, with each row on a new line and elements separated by spaces.

## Example

### Input

```
3
1 2 3
2 4 5
3 5 6
3
```

### Output

```
14 25 31
25 25 56
31 56 70
```

### Input

```
4
1 2 3 4
1 2 3 4
1 2 3 4
1 2 3 4
5
```

### Output

```
10000 20000 30000 40000
10000 20000 30000 40000
10000 20000 30000 40000
10000 20000 30000 40000
```
