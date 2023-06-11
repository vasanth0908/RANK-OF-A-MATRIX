RANK-OF-A-MATRIX
Aim:
To write a python program to find the rank of a matrix

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
Algorithm:
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Get the input matrix from the user

Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4:
End the program

Program:
```
#Program to find the rank of a matrix.

#Developed by: Vasanth S

#RegisterNumber: 212222110052

import numpy as np

A = np.array([[3,2,5],[1,1,2],[3,3,6]])

values=np.linalg.matrix_rank(A)

print(values)
```
OUTPUT:

Result:
Thus the rank for the given matrix is successfully solved by using a python program.

