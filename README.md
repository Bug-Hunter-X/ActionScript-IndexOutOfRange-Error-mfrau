# ActionScript IndexOutOfRange Bug

This repository demonstrates a common ActionScript error: `IndexOutOfRange`.  The error occurs when attempting to access an array element with an index that is out of bounds.

The `bug.as` file contains the buggy code, while `bugSolution.as` provides a corrected version.

## Bug Description
When iterating through an array, it's crucial to ensure the loop counter doesn't exceed the array's valid index range. The provided code attempts to access `myArray[myArray.length]`, which is always one element past the last valid element.