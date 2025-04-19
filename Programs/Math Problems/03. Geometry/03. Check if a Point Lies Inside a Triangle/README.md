# Check if a Point Lies Inside a Triangle

## Problem Statement

Given three points A, B, and C, determine if a point P lies inside a triangle ABC. The points are represented by their coordinates in a 2D plane.
The triangle is defined by its vertices A, B, and C, and the point P is given by its coordinates (x, y).

## Input

- The first line contains the coordinates of point A (Ax, Ay).
- The second line contains the coordinates of point B (Bx, By).
- The third line contains the coordinates of point C (Cx, Cy).
- The fourth line contains the coordinates of point P (Px, Py).
- The coordinates are given as integers.

## Output

- Print "Inside" if point P lies inside the triangle ABC.
- Print "On Edge" if point P lies on the edge of the triangle ABC.
- Print "Outside" if point P lies outside the triangle ABC.

## Example

### Input

```
1 1
2 3
3 1
1 2
```

### Output

```
Inside
```

### Input

```
1 2
2 3
3 1
1 1
```

### Output

```
On Edge
```

## Constraints

- The coordinates of the points are integers in the range [-1000, 1000].
- The triangle ABC is not degenerate (i.e., the points A, B, and C are not collinear).
- The point P can be any point in the 2D plane, including the vertices of the triangle and points on its edges.
