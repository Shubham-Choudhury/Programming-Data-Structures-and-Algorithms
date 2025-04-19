# Check Right-Angled Triangle (Pythagoras Theorem)

## Problem Statement

Check if a given set of three numbers can form a right-angled triangle using Pythagoras Theorem.
The Pythagorean theorem states that in a right-angled triangle, the square of the length of the hypotenuse (the side opposite the right angle) is equal to the sum of the squares of the lengths of the other two sides. This can be expressed mathematically as:
$$c^2 = a^2 + b^2$$
where:

- $c$ is the length of the hypotenuse.
- $a$ and $b$ are the lengths of the other two sides.

The goal is to determine if the given three numbers can be the lengths of the sides of a right-angled triangle.

## Input

Three numbers representing the lengths of the sides of a triangle.

## Output

A message indicating whether the numbers can form a right-angled triangle or not.
The output should be in the following format:

- "The numbers can form a right-angled triangle."
- "The numbers cannot form a right-angled triangle."

## Example

### Input

```
3 4 5
```

### Output

```
The numbers can form a right-angled triangle.
```

### Input

```
1 2 3
```

### Output

```
The numbers cannot form a right-angled triangle.
```

## Constraints

- The input numbers are positive integers.
- The numbers can be in any order.
