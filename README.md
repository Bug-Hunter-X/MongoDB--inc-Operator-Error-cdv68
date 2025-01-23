# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numeric field by a specified value.  However, an incorrect usage can lead to unexpected errors or incorrect updates.

The `bug.js` file showcases the incorrect implementation, where a string value is provided to `$inc`. The `bugSolution.js` file provides the correct implementation.