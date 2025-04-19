# Angle Between Two Vectors

## Problem Statement

Given two vectors $\mathbf{a}$ and $\mathbf{b}$, find the angle between them in degrees. The vectors are represented by their components in a 2D plane.
The angle is defined as the angle between the two vectors when they are placed tail to tail. The angle should be calculated using the dot product formula.

## Input

- The first line contains the components of vector $\mathbf{a}$ (Ax, Ay).
- The second line contains the components of vector $\mathbf{b}$ (Bx, By).
- The components are given as integers.

## Output

- Print the angle between the vectors in degrees, rounded to two decimal places.

## Example

### Input

```
1 2
3 4
```

### Output

```
26.57
```

### Input

```
0 0
1 1
```

### Output

```
90.0
```

## Constraints

- The components of the vectors are integers in the range [-1000, 1000].
- The angle should be rounded to two decimal places.

## Note

- The angle is calculated using the formula:
  $$\theta = \arccos\left(\frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{a}| |\mathbf{b}|}\right)$$
- The output should be formatted to two decimal places, even if the result is a whole number (e.g., 2.00).
