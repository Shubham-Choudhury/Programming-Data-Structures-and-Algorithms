# Polygon Area (Shoelace Formula)

## Problem Statement

The Shoelace formula is used to calculate the area of a simple polygon whose vertices are described by their Cartesian coordinates in the plane. The formula is given by:
$$A = \frac{1}{2} \left| \sum_{i=1}^{n} (x_i y_{i+1} - x_{i+1} y_i) \right|$$
where $(x_{n+1}, y_{n+1})$ is the same as $(x_1, y_1)$, and $n$ is the number of vertices.
The vertices should be given in either clockwise or counterclockwise order.

## Input

- The first line contains an integer $n$ (3 ≤ n ≤ 10^5), the number of vertices.
- The next $n$ lines each contain two integers $x_i$ and $y_i$ (1 ≤ $x_i$, $y_i$ ≤ 10^9), the coordinates of the vertices.
- The last line contains a string $s$ (1 ≤ |s| ≤ 10^5), the order of the vertices (either "clockwise" or "counterclockwise").

## Output

- Print the area of the polygon rounded to 2 decimal places.
- If the order of the vertices is "clockwise", print "Clockwise" followed by the area.
- If the order of the vertices is "counterclockwise", print "Counterclockwise" followed by the area.
- The area should be printed with 2 decimal places of precision.

## Example

### Input

```
5
0 0
1 0
1 1
1 3
0 3
clockwise
```

### Output

```
Clockwise 3.00
```

### Input

```
4
0 0
1 0
1 1
0 1
counterclockwise
```

### Output

```
Counterclockwise 1.00
```

## Constraints

- The vertices are distinct and form a simple polygon.
- The coordinates of the vertices are within the range of 1 to 10^9.
- The order of the vertices is either "clockwise" or "counterclockwise".
- The number of vertices is between 3 and 10^5.

