# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the Numpy library in your python scripit
### Step 2:
Define your matrix for which you wantyo find eigen values and eigenvectors
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the results
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: T Mounish
#RegisterNumber:23002806
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/MounishT/EIGENVALUES-AND-EIGENVECTORS/assets/138955798/a5b374c0-d673-4b7c-8406-0608feeadb5e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
