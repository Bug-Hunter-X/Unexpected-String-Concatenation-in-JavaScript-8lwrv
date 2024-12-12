# Unexpected String Concatenation in JavaScript

This code demonstrates a common error in JavaScript where loose typing leads to unexpected string concatenation instead of numerical addition.  The `add` function attempts to add two values, but if one is a string, the `+` operator performs string concatenation rather than numerical addition.

The solution demonstrates using `Number()` to explicitly convert the inputs to numbers before addition, ensuring the correct numerical result.