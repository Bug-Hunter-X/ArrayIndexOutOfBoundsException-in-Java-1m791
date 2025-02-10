# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its valid index range, resulting in this exception. The `bugSolution.java` file provides a corrected version.

**Problem:**
Incorrect array index access.  Attempting to access an array element using an index that is less than 0 or greater than or equal to the array's length.

**Solution:**
Ensuring that array indices are within the valid range (0 to array.length - 1).  Adding input validation or boundary checks can prevent this type of error.