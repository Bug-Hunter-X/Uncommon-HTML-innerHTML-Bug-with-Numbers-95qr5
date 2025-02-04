# Uncommon HTML Bug: innerHTML with Numbers

This repository demonstrates a subtle bug that can occur when using the `innerHTML` property in JavaScript with a number instead of a string.  Some browsers might handle this differently, leading to unexpected results or errors.

## Bug Description
The bug involves directly assigning a number to the `innerHTML` property.  While the code might appear to work in some cases, it's not the intended or consistent behavior.  This can lead to inconsistencies across browsers and potential issues in more complex applications.

## Solution
Always convert the number to a string before assigning it to `innerHTML` to ensure consistent and predictable behavior across different browsers and environments.