# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`. The code attempts to access an array element beyond its bounds, leading to a runtime exception.

## Bug Description
The `for` loop iterates one time too many. The loop condition `i <= arr.length` should be `i < arr.length`.  The array is of length 5, valid indices are 0-4, but the incorrect loop condition tries to access index 5.

## Solution
The solution corrects the loop condition to ensure that the loop terminates before trying to access an invalid array index.