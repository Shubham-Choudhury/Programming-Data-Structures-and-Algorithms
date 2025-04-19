# Fast Exponentiation (a^b)

## Problem Statement

Write a function to calculate the value of `a^b` (a raised to the power of b) using fast exponentiation.

## Input

- Two integers `a` and `b` (1 ≤ a, b ≤ 10^9)

## Output

- Print the value of `a^b`.

## Example

### Input

```
2 10
```

### Output

```
1024
```

### Input

```
4 5
```

### Output

```
1024
```

### Explanation

- The value of 2^10 is 1024.
- The value of 4^5 is 1024.

### Constraints

- The input numbers `a` and `b` are guaranteed to be positive integers.

## Note

- Fast exponentiation is an efficient method to compute large powers of a number using the divide-and-conquer approach.
- The time complexity of this algorithm is O(log b).
- The space complexity is O(1) if we do not consider the recursion stack.

## Algorithm

1. Initialize a variable `result` to 1.
2. While `b` is greater than 0:
   - If `b` is odd, multiply `result` by `a`.
   - Divide `b` by 2 (integer division).
   - Square the value of `a`.
3. Return `result`.
