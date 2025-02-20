# Type 'string[]' is not assignable to type 'string'
This repository demonstrates a common TypeScript error: providing an array of strings to a function expecting a single string.
The `bug.ts` file shows the erroneous code.  The `bugSolution.ts` file provides a corrected version.

This error arises frequently when working with functions that expect specific input types and data isn't pre-processed correctly before being passed as an argument.

Solutions involve careful type checking and handling arrays appropriately, perhaps by iterating through the array or using a different function signature.
