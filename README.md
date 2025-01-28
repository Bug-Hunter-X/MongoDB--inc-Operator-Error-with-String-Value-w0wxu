# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numeric field by a specified value.  However, attempting to increment with a non-numeric value will result in an error.

## Bug
The `bug.js` file contains code that attempts to increment a field using a string value. This will cause a MongoDB error. 

## Solution
The `bugSolution.js` file demonstrates the corrected code, incrementing the field using the correct numeric type.