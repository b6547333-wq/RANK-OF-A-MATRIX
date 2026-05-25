# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and input the matrix elements along with the number of rows and columns.
### Step 2: Convert the matrix into row echelon form using elementary row operations (swap rows, multiply rows, subtract rows).
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix and stop the program.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: J Mohamed Arsath
#RegisterNumber:212225040237
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Given matrix
A = np.array([
    [1, 2, 3],
    [3, 6, 9],
])

# Find rank
rank = np.linalg.matrix_rank(A)

print(rank)

```
## Output:
<img width="1257" height="838" alt="image" src="https://github.com/user-attachments/assets/e7d7323b-9c7f-44a3-b161-2a03cc9cc14b" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

