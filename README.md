# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in function for calculation
### Step 2: 
prepare the list from each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:R.sheetal
#RegisterNumber:212223230206
import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:

![Screenshot 2024-05-08 225440](https://github.com/Sheetalshee/EIGENVALUES-AND-EIGENVECTORS/assets/144979107/b13885b8-9f44-46fb-ab95-e1d7a22c1dbe)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
