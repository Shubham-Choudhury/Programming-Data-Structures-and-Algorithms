# Convex Hull (Graham Scan Algorithm)

## Problem Statement

Given a set of 2D points, find the convex hull of the points using the Graham Scan algorithm. The convex hull is the smallest convex polygon that can enclose all the points.
The algorithm works by first finding the point with the lowest y-coordinate (and leftmost in case of a tie), then sorting the points based on their polar angle with respect to this point, and finally constructing the convex hull using a stack.

## Input

- The first line contains an integer $n$ (1 ≤ n ≤ 10^5), the number of points.
- The next $n$ lines each contain two integers $x_i$ and $y_i$ (1 ≤ $x_i$, $y_i$ ≤ 10^9), the coordinates of the points.

## Output

- Print the points in the convex hull in counter-clockwise order, starting from the point with the lowest y-coordinate. If there are multiple points with the same y-coordinate, print the leftmost one first.
- Each point should be printed on a new line in the format "x y".

## Example

### Input

```
5
0 0
1 1
2 2
3 1
4 0
```

### Output

```
0 0
1 1
2 2
3 1
4 0
```

### Input

```
5
2 3
1 4
1 2
0 1
2 0
```

### Output

```
0 1
1 2
1 4
2 3
2 0
```

## Constraints

- The input points are distinct.
- The output points should be distinct and in counter-clockwise order.

## Note

- The Graham Scan algorithm has a time complexity of O(n log n) due to the sorting step, and O(n) for the construction of the convex hull.
- The algorithm is efficient for large datasets and can handle up to 10^5 points.
