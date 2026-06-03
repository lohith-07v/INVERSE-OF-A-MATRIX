# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the required NumPy library.
### Step 2: Define the matrix A.
### Step 3: Use numpy.linalg.inv() to find the inverse of the matrix.
### Step 4: Print the inverse matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Lohith v
#RegisterNumber:212225230154
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Define the matrix
A = np.array([[2,1,1], [1,1,1], [1,-1,2]])

# Calculate the inverse
result = np.linalg.inv(A)

# Print the result
print( result)
```

## Output:
![alt text](<Screenshot 2026-06-03 114043.png>)
![alt text](<Screenshot 2026-06-03 114052.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

