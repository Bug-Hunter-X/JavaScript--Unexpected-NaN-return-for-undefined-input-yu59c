# JavaScript Bug: Unexpected NaN Return for undefined Input

This repository demonstrates a common error in JavaScript: incorrect handling of `undefined` values.

The `foo` function correctly handles `null` inputs by returning 0. However, when an `undefined` value is passed, it results in `NaN` because adding 1 to `undefined` is not a defined operation.

**Bug:**
The `foo` function doesn't handle `undefined` values gracefully, leading to unexpected `NaN` results.

**Solution:**
The solution file addresses this by explicitly checking for `undefined` and handling it appropriately (returning 0 in this case).  This prevents `NaN` and provides a more robust and predictable function.

This example illustrates the importance of considering all possible input types and handling edge cases when writing JavaScript functions.