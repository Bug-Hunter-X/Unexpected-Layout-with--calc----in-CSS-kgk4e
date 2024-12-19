# Unexpected Layout with `calc()` in CSS

This repository demonstrates a common error when using the `calc()` function in CSS, specifically how it can interact unexpectedly with flexbox and percentage-based widths.

The `bug.css` file contains the problematic code, while `bugSolution.css` shows the corrected approach.

## Bug Description
The `calc()` function is used to perform calculations within CSS. However, improper usage, particularly within flexbox layouts or when percentage values are involved, can result in unexpected results.

## Solution
Understanding the context of the calculation is key to using `calc()` correctly. Ensuring that the parent container has a defined width is crucial when dealing with percentages in `calc()` within flexbox layouts. 