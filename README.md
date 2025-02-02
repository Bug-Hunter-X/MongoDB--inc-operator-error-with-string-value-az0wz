# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The error arises from providing a string value to `$inc` instead of a number, leading to unexpected results. The solution shows the correct way to increment a field using `$inc`.

## Bug
The bug lies in using a string ('1') instead of a number (1) with the `$inc` operator. This results in the field not being incremented correctly, potentially leading to data corruption or unexpected application behavior.