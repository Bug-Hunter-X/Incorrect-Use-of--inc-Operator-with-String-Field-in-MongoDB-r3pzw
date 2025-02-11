# Incorrect Use of $inc Operator with String Field in MongoDB
This repository demonstrates a common error in MongoDB when using the `$inc` operator with a string field.  The `$inc` operator is designed to increment numeric values; applying it to a string field results in an error. The solution showcases the proper method for handling updates to string fields. 

## Bug
The `bug.js` file contains code that attempts to increment a string field using `$inc`. This will cause a MongoDB error.

## Solution
The `bugSolution.js` file demonstrates the correct way to handle this situation.  Instead of `$inc`, you should use `$set` to update the string field with a modified value. 
