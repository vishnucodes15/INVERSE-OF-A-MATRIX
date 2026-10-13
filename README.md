# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Importing the Numpy Module as np
### Step 2: Creating the given matrix as an array using np.array() function
### Step 3: Finding the inverse of the given matrix using the np.linalg.inv() funtion
### Step 4: Printing the result

## Program:
#Program to find the inverse of a matrix.
#Developed by: Sre Vishnu Priyar L N
#RegisterNumber: 26009605

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
print(np.linalg.inv(A))
## Output:
<img width="1367" height="952" alt="image" src="https://github.com/user-attachments/assets/e087030f-ff3e-4e73-86d7-351420799446" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

