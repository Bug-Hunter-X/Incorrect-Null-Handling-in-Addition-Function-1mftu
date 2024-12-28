# Incorrect Null Handling in Addition Function

This repository demonstrates a common error in JavaScript: incorrect handling of null values. The `foo` function is designed to add two numbers, but it incorrectly handles null values by simply returning 0.  This can lead to unexpected results and bugs in applications.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version that handles null values more gracefully.

## Bug
The `foo` function returns 0 if either `a` or `b` is null.  This is incorrect. A more robust solution would treat null values as 0 for the purposes of addition.  The bug is that the function does not differentiate between null and 0 as inputs.