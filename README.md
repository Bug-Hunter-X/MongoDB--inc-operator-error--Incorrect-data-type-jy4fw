# MongoDB $inc Operator Error: Incorrect Data Type

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical value in a document.  However, if you provide a non-numerical value (such as a string), the operation will fail or produce unexpected results.

The `bug.js` file showcases the incorrect usage, where we attempt to increment a counter field using a string value. The `bugSolution.js` file provides the correct implementation, ensuring that the value being incremented is a number.

## How to reproduce the bug

1.  Clone this repository.
2.  Connect to your MongoDB instance.
3.  Run `bug.js`.
4.  Observe the error or unexpected behavior.

## Solution

The `bugSolution.js` demonstrates the corrected implementation using the correct numeric value for the counter.