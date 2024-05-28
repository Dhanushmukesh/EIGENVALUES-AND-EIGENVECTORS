# EIGENVALUES-AND-EIGENVECTORS
#DATE:
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Dhanush.G
#RegisterNumber:2305002006
```
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-05-28 085344](https://github.com/Dhanushmukesh/EIGENVALUES-AND-EIGENVECTORS/assets/155508176/9474488c-5b29-4db1-8a85-5e7b57982f2c)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
