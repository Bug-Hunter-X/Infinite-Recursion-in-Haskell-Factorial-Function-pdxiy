# Haskell Factorial Function Bug
This repository demonstrates a common error in Haskell: infinite recursion due to incomplete pattern matching. The `factorialBug.hs` file contains the buggy code, which doesn't explicitly handle negative input, resulting in a stack overflow.  The solution, `factorialSolution.hs`, provides a corrected version.

**How to reproduce:**
1. Clone this repository.
2. Compile and run `factorialBug.hs` with a negative input (e.g., `factorialBug -5`).  Observe the stack overflow error.
3. Compile and run `factorialSolution.hs` to see the corrected behavior.