# Exp-04-EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: P.LOKNAATH
#RegisterNumber: 212223240080

import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
~~~
## Output:
![image](https://github.com/Loknaath-sec/EIGENVALUES-AND-EIGENVECTORS/assets/145742558/a3d3fe93-37c6-4b52-a389-f7d862d2d748)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
