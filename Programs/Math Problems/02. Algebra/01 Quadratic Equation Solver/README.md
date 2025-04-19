# Quadratic Equation Solver

## Problem Statement
Solve the quadratic equation $ax^2 + bx + c = 0$ for $x$ where $a$, $b$, and $c$ are real numbers and $a \neq 0$.
The solutions can be found using the quadratic formula:

$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

The discriminant $D = b^2 - 4ac$ determines the nature of the roots:
- If $D > 0$, there are two distinct real roots.
- If $D = 0$, there is one real root (a double root).
- If $D < 0$, there are two complex roots.

## Input
- Three real numbers $a$, $b$, and $c$ where $a \neq 0$.
- The coefficients can be positive or negative real numbers.

## Output
- Print the roots of the quadratic equation in the following format:
  - If $D > 0$: "x1 = value1, x2 = value2"
  - If $D = 0$: "x = value"
  - If $D < 0$: "x1 = value1 + value2i, x2 = value3 - value4i"
- The roots should be printed with 2 decimal places of precision.
- The complex roots should be printed in the form of "a + bi" and "a - bi" where $a$ is the real part and $b$ is the imaginary part.
- The imaginary unit $i$ is represented as "i" in the output.
- The real and imaginary parts should be rounded to 2 decimal places.

## Example

### Input
```
2 -4 2
```
### Output
```
x1 = -0.00, x2 = 1.00
```

### Input
```
1 2 3
```
### Output
```
x = -1.00
```
### Input
```
1 2 -3
```
### Output
```
x1 = 1.41 + 0.41i, x2 = 1.41 - 0.41i
```

## Explanation
- For the first input, the discriminant is positive, so there are two distinct real roots.
- For the second input, the discriminant is zero, so there is one real root (a double root).
- For the third input, the discriminant is negative, so there are two complex roots.
- The roots are calculated using the quadratic formula and printed in the specified format.
- The real and imaginary parts are rounded to 2 decimal places for clarity.

## Constraints
- The coefficients $a$, $b$, and $c$ are real numbers.
- The coefficient $a$ is non-zero.
- The input values can be positive or negative real numbers.
