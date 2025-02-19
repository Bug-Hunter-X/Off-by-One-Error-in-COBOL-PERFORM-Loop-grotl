# Off-by-One Error in COBOL PERFORM Loop

This example demonstrates a common off-by-one error in a COBOL PERFORM loop. The loop intends to iterate 10 times, but due to an error in the loop condition, it either iterates 9 or 11 times.  This can cause issues in applications where precise iteration counts are crucial.

The `bug.cob` file shows the erroneous code, while `bugSolution.cob` provides the corrected version.

## How to Reproduce
1. Compile and run `bug.cob`. Observe the incorrect counter value.
2. Compile and run `bugSolution.cob`. Observe the corrected counter value.