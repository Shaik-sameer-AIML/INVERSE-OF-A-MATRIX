# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array() 
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program

## Program:
#Program to find the rank of a matrix.

#Developed by: shaik sameeer

#RegisterNumber:21003881

import numpy as np

A=np.array ([[1,2,3],[3,6,9]])

sol=np.linalg.matrix_rank(A)

print(sol)
## Output:
![output](https://github.com/Shaik-sameer-AIML/INVERSE-OF-A-MATRIX/blob/main/inverse%20of%20a.PNG?raw=true)
## Result:
Thus the inverse of given matrix is successfully solved using python program

