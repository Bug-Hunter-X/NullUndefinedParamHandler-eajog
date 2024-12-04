# JavaScript Null and Undefined Handling

This repository demonstrates a common error in JavaScript:  improperly handling `null` or `undefined` values passed as function arguments.  The `bug.js` file contains code with this issue, while `bugSolution.js` shows the corrected version.

The problem typically arises when a function expects a specific data type but receives `null` or `undefined`. Without proper checks, this can lead to unexpected results or runtime errors.  This example shows how to implement a check for null or undefined values before processing them.

## How to reproduce the bug

Execute the code in `bug.js`. Note the error when a null value is passed to the function.

## How to solve the bug

Review and implement the solution presented in `bugSolution.js`. The solution is straightforward: add a check at the beginning of the function to handle null or undefined values gracefully.