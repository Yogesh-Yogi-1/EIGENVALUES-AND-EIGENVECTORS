# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built - in functions for calculation.
### Step 2: 
Create a list and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
\*
#Program to find the eigen values and eigen vectors.
#Developed by: V. Yogesh
#RegisterNumber:23013930
\*
import numpy as np
A=[-2,2,-3],[2,1,-6],[-1,-2,0]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot 2023-12-19 200507](https://github.com/Yogesh-Yogi-1/EIGENVALUES-AND-EIGENVECTORS/assets/148514598/e1ed1c3e-027e-44d5-91c6-8bb6dbdb937c)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
