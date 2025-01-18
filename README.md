# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException`. The `BuggyArray.java` file contains code that attempts to access an array element beyond its valid index range, causing the exception. The corrected version (`CorrectedArray.java`) shows how to fix the problem by adjusting the loop condition.

**How to reproduce the bug:**
1. Compile `BuggyArray.java`.
2. Run the compiled class.
3. Observe the `ArrayIndexOutOfBoundsException`. 

**Solution:**
The `CorrectedArray.java` file shows the solution: changing the loop condition to `i < arr.length` prevents the index from exceeding the valid range. 