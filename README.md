# JavaScript Type Coercion Pitfall: String Concatenation Instead of Number Addition

This example demonstrates a common type coercion issue in JavaScript where the `+` operator performs string concatenation instead of numerical addition when one of the operands is a string.

The `bug.js` file contains the erroneous code that results in unexpected string concatenation.

The `bugSolution.js` file provides the corrected code that explicitly converts the operands to numbers before performing the addition.

## How to reproduce
1. Clone this repository.
2. Run `node bug.js` to observe the unexpected output.
3. Run `node bugSolution.js` to see the corrected output.