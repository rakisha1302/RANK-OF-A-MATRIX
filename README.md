# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
#Step 1: Import the NumPy module to use mathematical and matrix functions.
#Step 2: Create a matrix using np.array() and store it in a variable A.
#Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
#Step 4: Print the value of X to display the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:Rakisha R 
#RegisterNumber:212225230223
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(matrixA)
print(rank)
```
## Output:
<img width="1345" height="826" alt="image" src="https://github.com/user-attachments/assets/da094298-c5d5-494f-b337-6f1f11c77556" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

