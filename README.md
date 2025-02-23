# Type Error in TypeScript Addition Function

This repository demonstrates a common type error in TypeScript when performing arithmetic operations with incorrectly typed variables.  The `add` function is defined to accept two numbers, but the code attempts to pass a string, leading to a type error.

## How to Reproduce

1. Clone the repository.
2. Compile the TypeScript code: `tsc bug.ts`
3. Observe the type error in the compiler output.

## Solution

The solution involves ensuring that both arguments passed to the `add` function are of the correct type (number). This can be done through type checking or type assertion before the addition takes place.  See `bugSolution.ts` for a corrected version.