# Sum of `n` Terms of Arithmetic / Geometric Series

## Problem Statement

The sum of the first `n` terms of an arithmetic series is given by the formula:

$S_n = \frac{n}{2} (2a + (n - 1)d)$

where:

- $S_n$ is the sum of the first `n` terms
- `a` is the first term of the series
- `d` is the common difference between consecutive terms
- `n` is the number of terms

The sum of the first `n` terms of a geometric series is given by the formula:

$S_n = a \frac{1 - r^n}{1 - r}$

where:

- $S_n$ is the sum of the first `n` terms
- `a` is the first term of the series
- `r` is the common ratio between consecutive terms
- `n` is the number of terms

## Input

- The first line contains three integers `a`, `d`, and `n` for the arithmetic series.
- The second line contains three integers `a`, `r`, and `n` for the geometric series.
- The values of `a`, `d`, and `r` can be positive or negative integers.
- The value of `n` is a positive integer.

## Output

- Print the sum of the first `n` terms of the arithmetic series in the following format:
  - "Sum of Arithmetic Series: S_n = value"
- Print the sum of the first `n` terms of the geometric series in the following format:
  - "Sum of Geometric Series: S_n = value"
- The sums should be printed with 2 decimal places of precision.

## Example

### Input

```
2 3 5
2 3 5
```

### Output

```
Sum of Arithmetic Series: S_n = 45.00
Sum of Geometric Series: S_n = 242.00
```

### Input

```
3 2 4
2 4 3
```

### Output

```
Sum of Arithmetic Series: S_n = 30.00
Sum of Geometric Series: S_n = 30.00
```

### Input

```
-5 2 6
2 3 4
```

### Output

```
Sum of Arithmetic Series: S_n = 66.00
Sum of Geometric Series: S_n = 80.00
```

## Explanation

- For the first input, the arithmetic series starts at 2 with a common difference of 3, and the sum of the first 5 terms is calculated as 45. The geometric series starts at 2 with a common ratio of 3, and the sum of the first 5 terms is calculated as 242.
- For the second input, the arithmetic series starts at 3 with a common difference of 2, and the sum of the first 4 terms is calculated as 30. The geometric series starts at 2 with a common ratio of 4, and the sum of the first 3 terms is calculated as 30.
- For the third input, the arithmetic series starts at -5 with a common difference of 2, and the sum of the first 6 terms is calculated as 66. The geometric series starts at 2 with a common ratio of 3, and the sum of the first 4 terms is calculated as 80.
- The sums are calculated using the respective formulas and printed in the specified format with 2 decimal places of precision.

## Constraints

- The values of `a`, `d`, and `r` can be positive or negative integers.
- The value of `n` is a positive integer.
