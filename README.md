# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions for caluculation
### Step 2: 
Get the input matrix from the user
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: T.Ajay
#RegisterNumber:23007325
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Ajayreddy-2006/EIGENVALUES-AND-EIGENVECTORS/assets/145742508/83124bfa-bdc2-4b53-86c2-f391ee85faf5)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
