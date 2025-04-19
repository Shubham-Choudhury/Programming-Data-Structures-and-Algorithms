# Intersection of Two Lines (Using Determinants)

## Problem Statement

Find the intersection point of two lines given by their parametric equations. The first line is defined by the points $(x_1, y_1)$ and $(x_2, y_2)$, and the second line is defined by the points $(x_3, y_3)$ and $(x_4, y_4)$.

## Input

- The first line contains four integers $x_1$, $y_1$, $x_2$, $y_2$ ($1 \leq x_1, y_1, x_2, y_2 \leq 10^9$), the coordinates of the first line.
- The second line contains four integers $x_3$, $y_3$, $x_4$, $y_4$ ($1 \leq x_3, y_3, x_4, y_4 \leq 10^9$), the coordinates of the second line.

## Output

- If the lines intersect, print "Intersect" followed by the coordinates of the intersection point rounded to 2 decimal places.
- If the lines do not intersect, print "Do not intersect".
- If the lines are parallel, print "Parallel".
- If the lines are coincident, print "Coincident".
- The coordinates of the intersection point should be printed with 2 decimal places of precision.

## Example

### Input

```
4 2 6 4
3 1 5 3
```

### Output

```
Intersect 4.00 3.00
```

### Input

```
1 1 3 3
1 2 3 4
```

### Output

```
Coincident
```

## Constraints

- The coordinates of the points are within the range of 1 to 10^9.
- The lines are defined by distinct points.

## Note

- The lines are considered coincident if they overlap completely.
- The lines are considered parallel if they do not intersect and are not coincident.
- The intersection point should be calculated using determinants and should be rounded to 2 decimal places.
- The output should be formatted to 2 decimal places.
- The coordinates of the intersection point should be printed with 2 decimal places of precision.
