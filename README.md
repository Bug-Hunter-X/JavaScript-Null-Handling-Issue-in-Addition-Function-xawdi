# JavaScript Null Handling Issue

This repository demonstrates a common error in JavaScript where null values are not handled properly, leading to unexpected behavior or errors.  The `bug.js` file contains a function that attempts to add two numbers, but it does not correctly handle null values. The `bugSolution.js` file provides a corrected version of the function. 

## Bug Description

The original function `foo` does not correctly handle null inputs. When either `a` or `b` is null, the addition operation will produce unexpected results, depending on the JavaScript engine, or throw an error.   The solution improves error handling and clarity.