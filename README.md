# Unexpected Behavior with Null Values in JavaScript Function

This repository demonstrates a common bug in JavaScript related to null value handling. The function `foo` does not explicitly handle cases where both `a` and `b` are null, which can lead to unexpected behavior.

## Bug Description
The function `foo` aims to add two numbers. However, if either `a` or `b` is null, the function returns without performing the addition.  The issue arises when both `a` and `b` are null; the function still returns `undefined` instead of handling this case more gracefully.

## Solution
The provided solution improves the function to explicitly check for both `a` and `b` being null before attempting addition.  This ensures consistent and predictable behavior across all input scenarios.