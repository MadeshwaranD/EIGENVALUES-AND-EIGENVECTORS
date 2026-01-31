# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
##Step 1: Import the NumPy library using import numpy as np.
##Step 2: Define the square matrix using np.array().
##Step 3: Use the function np.linalg.eig() to compute the eigenvalues and eigenvectors of the matrix.
##Step 4: Display the obtained eigenvalues and eigenvectors.
 That’s it. Four steps. Simple and mathematically honest.

## Program:
...
**#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))**
...

## Output:
<img width="1486" height="860" alt="image" src="https://github.com/user-attachments/assets/efa3c04a-f1ad-4605-bd39-ab4a2898d58e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
