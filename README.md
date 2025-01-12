# Unexpected 0 Return for Null Inputs in Addition Function

This repository demonstrates a subtle bug in JavaScript related to the handling of null values in an addition function. The function `foo` returns 0 when either input `a` or `b` is null, while a more intuitive and often expected behavior would be to return null in such cases.

## Bug Description
The `foo` function performs addition of two numbers. However, it incorrectly handles null inputs, returning 0 instead of null.

## Bug Solution
The solution involves modifying the function to explicitly return null when either input is null, providing a more consistent and expected behavior.