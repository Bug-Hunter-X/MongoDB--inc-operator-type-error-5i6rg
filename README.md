# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, if a string is provided as the increment value, it will lead to unexpected behavior.

## Bug
The `bug.js` file contains code that attempts to increment a field using a string value with `$inc`. This results in an error or unintended behavior.

## Solution
The `bugSolution.js` file provides the corrected code, ensuring that the increment value is a number.  This ensures the `$inc` operator functions correctly.

## How to reproduce
1. Clone this repository.
2. Run `bug.js` and observe the error or unexpected results.
3. Run `bugSolution.js` and verify the correct behavior.
