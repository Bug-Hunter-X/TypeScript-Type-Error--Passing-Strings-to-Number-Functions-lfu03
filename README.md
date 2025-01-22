# TypeScript Type Error Example

This repository demonstrates a common type error in TypeScript: passing a string argument to a function expecting a number.  The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides a corrected version.

The error arises because TypeScript's type system enforces type safety. The functions `add` and `subtract` are explicitly defined to only accept numeric arguments.  Attempts to provide string arguments violate this type constraint, resulting in a compilation error.

The solution involves either ensuring only numbers are passed to the functions or employing type guards or type assertions to handle potential string inputs gracefully (as shown in `bugSolution.ts`).