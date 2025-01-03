# MongoDB $inc operator with string value

This repository demonstrates an uncommon error in MongoDB update operations involving the `$inc` operator. The `$inc` operator is designed to increment a numeric field, but it can throw an error if the provided value is not a number.  This example shows the incorrect usage and provides the corrected solution.

**Bug:** The original code attempts to increment a field using a string value. MongoDB expects a numeric value for `$inc` operations. This results in an error.

**Solution:** The solution demonstrates the correct usage of the `$inc` operator, providing a numeric value to increment the field appropriately.