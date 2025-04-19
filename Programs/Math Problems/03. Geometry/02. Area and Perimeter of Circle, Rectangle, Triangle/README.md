# Area and Perimeter of Circle, Rectangle, Triangle

## Problem Statement

Calculate the area and perimeter of a circle, rectangle, and triangle.
The formulas for each shape are as follows:

- Circle:

  - Area: $A = \pi r^2$
  - Perimeter (Circumference): $P = 2 \pi r$

- Rectangle:

  - Area: $A = l \times w$
  - Perimeter: $P = 2(l + w)$

- Triangle:
  - If Right-angled:
    - Area: $A = \frac{1}{2} \times b \times h$ (where $b$ is the base and $h$ is the height)
  - If not right-angled:
    - Area: $A = \sqrt{s(s-a)(s-b)(s-c)}$ (where $s = \frac{a+b+c}{2}$ is the semi-perimeter and $a$, $b$, and $c$ are the lengths of the sides)
  - Perimeter: $ P = a + b + c $ (where $a$, $b$, and $c$ are the lengths of the sides)

## Input

- The first line contains radius $r$ of the circle.
- The second line contains length $l$ and width $w$ of the rectangle.
- The third line contains the lengths of the sides $a$, $b$, and $c$ of the triangle.

## Output

- Print the area and perimeter of the circle, rectangle, and triangle in the following format:
  - Circle: Area = value, Perimeter = value
  - Rectangle: Area = value, Perimeter = value
  - Triangle: Area = value, Perimeter = value
- The values should be printed with 2 decimal places of precision.

## Example

### Input

```
3
4 5
6 8 10
```

### Output

```
Circle: Area = 28.27, Perimeter = 18.85
Rectangle: Area = 20.00, Perimeter = 18.00
Triangle: Area = 24.00, Perimeter = 24.00
```

### Input

```
5
12 3
7 19 13
```

### Output

```
Circle: Area = 78.54, Perimeter = 31.42
Rectangle: Area = 36.00, Perimeter = 30.00
Triangle: Area = 42.00, Perimeter = 39.00
```

### Input

```
12
8 4
3 5 4
```

### Output

```
Circle: Area = 452.39, Perimeter = 75.86
Rectangle: Area = 32.00, Perimeter = 24.00
Triangle: Area = 6.00, Perimeter = 12.00
```

## Constraints

- The radius $r$ of the circle is a positive real number.
- The length $l$ and width $w$ of the rectangle are positive real numbers.
- The lengths of the sides $a$, $b$, and $c$ of the triangle are positive real numbers.
- The triangle inequality holds for the lengths of the sides (i.e., the sum of the lengths of any two sides is greater than the length of the third side).
- The triangle is not necessarily right-angled.
