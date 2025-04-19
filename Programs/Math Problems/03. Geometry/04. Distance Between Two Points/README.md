# Distance Between Two Points

## Problem Statement

Given two points A and B in a 2D plane, represented by their coordinates (Ax, Ay) and (Bx, By), calculate the distance between them. The distance is defined as the Euclidean distance, which is the length of the straight line connecting the two points.

## Input

- The first line contains the coordinates of point A (Ax, Ay).
- The second line contains the coordinates of point B (Bx, By).
- The coordinates are given as integers.

## Output

- Print the distance between points A and B, rounded to two decimal places.

## Example

### Input

```
1 2
3 4
```

### Output

```
4.47
```

### Input

```
5 6
7 8
```

### Output

```
2.83
```

## Constraints

- The coordinates of the points are integers in the range [-1000, 1000].
- The distance should be rounded to two decimal places.

## Note

- The distance is calculated using the formula:
  $d = \sqrt{(Bx - Ax)^2 + (By - Ay)^2}$
- The output should be formatted to two decimal places, even if the result is a whole number (e.g., 2.00).
