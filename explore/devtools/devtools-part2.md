# DevTools Part 2

## 1.

The bug was that the input values were being treated as strings instead of numbers. Because of this, JavaScript used string concatenation instead of numeric addition. For example, `2 + 3` became `"23"` instead of `5`.

## 2.

To fix the bug, I would convert the input values to numbers before adding them.

Original code:

    let result = num1 + num2;

Fixed code:

    let result = Number(num1) + Number(num2);

After this change, the program correctly calculates the sum as a number.
