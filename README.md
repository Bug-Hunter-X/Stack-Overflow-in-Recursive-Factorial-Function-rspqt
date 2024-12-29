# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow.  The `foo` function calculates the factorial of a number recursively.  For large inputs, the recursion depth exceeds the system's stack limit, resulting in a stack overflow error.

The solution demonstrates how to avoid this by using iteration instead of recursion.