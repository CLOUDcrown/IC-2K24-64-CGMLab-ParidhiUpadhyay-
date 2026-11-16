# CGM Lab Assignment 2 - DDA Line Drawing Algorithm

## Aim

To implement the DDA (Digital Differential Analyzer) Line Drawing Algorithm using C++ graphics.

## Objective

To understand and implement the DDA Line Drawing Algorithm for drawing a straight line in computer graphics.

## Requirements

- C++
- graphics.h
- WinBGIm graphics library

## Algorithm

1. Start the program.
2. Read the starting point `(x1, y1)`.
3. Read the ending point `(x2, y2)`.
4. Calculate:
   
   `dx = x2 - x1`

   `dy = y2 - y1`

5. Calculate the number of steps:

   `steps = max(|dx|, |dy|)`

6. Calculate:

   `xinc = dx / steps`

   `yinc = dy / steps`

7. Set `x = x1` and `y = y1`.
8. Plot the pixel at `(round(x), round(y))`.
9. Increase x and y using the increments.
10. Repeat until all steps are completed.
11. Display the line graphically.
12. Stop the program.

## Source Code

The source code is available in `dda.cpp`.

## Sample Input

```text
Enter starting point (x1 y1): 100 200
Enter ending point (x2 y2): 300 400
