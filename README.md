# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The error arises from using a string instead of a numeric value for the increment.

## Bug
The `bug.js` file contains code that attempts to increment a counter field using the `$inc` operator with a string value. This results in the counter field not being incremented correctly. 

## Solution
The `bugSolution.js` file provides the corrected code using a numeric value with the `$inc` operator, thus resolving the increment issue.

## How to Reproduce
1. Clone this repository.
2. Run `bug.js`. Observe the incorrect result.
3. Run `bugSolution.js`. Observe the correct result.
