# Type Error in TypeScript
This example demonstrates a common type error in TypeScript: passing an array to a function that expects a string.

The `greeter` function is defined to accept a string argument. However, the `user` variable is an array of strings. When `greeter(user)` is called, TypeScript throws an error because the types are incompatible.

The solution shows how to fix this error by either changing the function signature to accept an array or by accessing the individual elements of the array before passing them to the function.