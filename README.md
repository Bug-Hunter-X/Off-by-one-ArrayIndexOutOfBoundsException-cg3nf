# Off-by-one ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common off-by-one error in Java that results in an `ArrayIndexOutOfBoundsException`. The error occurs when iterating over an array and incorrectly using the `<=` operator in the loop condition. This causes an attempt to access an index that is out of bounds, resulting in the exception.

The `Bug.java` file contains the erroneous code, while `BugSolution.java` provides the corrected version.  The solution simply changes the loop condition to `<` to prevent exceeding the array's valid indices.

This example highlights the importance of careful array index management in programming.