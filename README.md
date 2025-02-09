# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs in the first for loop, where the loop condition `i <= arr.length` causes an attempt to access an index beyond the array's bounds. 

The bug is described in `bug.java`. A corrected version is provided in `bugSolution.java`.