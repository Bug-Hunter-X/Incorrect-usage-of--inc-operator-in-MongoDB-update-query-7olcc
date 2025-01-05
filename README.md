# MongoDB $inc Operator Error
This repository demonstrates an uncommon error encountered when using the `$inc` operator in MongoDB update queries. The `$inc` operator is designed to increment a numeric field by a specified value, but using a string value instead will lead to an error. The solution shows the correct usage with a numeric value for incrementing the age field. 

## Bug
The provided code snippet showcases an incorrect usage of the `$inc` operator, attempting to increment the 'age' field by the string value '1'. This results in a MongoDB error.

## Solution
The solution demonstrates the correct usage of the `$inc` operator with a numeric value for a successful update.