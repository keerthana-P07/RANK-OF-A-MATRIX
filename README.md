# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from each linear equations and assign in np.array()
Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
 Step 4: End the Program
## Program:
```
#Program to find the rank of a matrix.
#Developed by:P KEERTHANA  
#RegisterNumber: 212225230138
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA = np.array([[3, 2, 5],
                    [1, 1, 2],
                    [3, 3, 6]])
result = np.linalg.matrix_rank(matrixA)
print(result)
```
## Output:
![alt text](<Screenshot 2026-08-11 105532.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

