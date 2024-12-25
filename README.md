# JavaScript Function: Unexpected Behavior with Undefined Values

This repository demonstrates a subtle bug in a simple JavaScript function that handles null values but unexpectedly behaves differently with undefined values. 
The function `foo` is intended to add two numbers together, but it returns null if either of its arguments is null. However, it doesn't explicitly handle cases where the arguments are undefined, resulting in unexpected behavior.

The `bug.js` file contains the buggy code, while `bugSolution.js` presents a refined version that correctly handles both null and undefined values.

This example highlights the importance of comprehensive null and undefined checks in JavaScript functions to prevent unexpected behavior and ensure robust code.