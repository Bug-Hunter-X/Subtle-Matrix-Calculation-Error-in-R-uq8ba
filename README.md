# Subtle Matrix Calculation Error in R

This repository demonstrates a common, yet subtle, error in R when performing matrix calculations. The code attempts to multiply a matrix by a scalar but uses the wrong operator leading to an incorrect result instead of a clear error message.  The solution provides the correct approach.

## Bug
The `bug.R` file contains the erroneous code. The error lies in attempting to multiply a matrix by a scalar using the `%*%` operator which is meant for matrix multiplication. This results in element-wise multiplication instead of the intended scalar multiplication.