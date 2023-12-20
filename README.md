# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
open python
### Step 2:
import numpy package
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print the result

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: R Shashank
#RegisterNumber:23013949
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Shashank2006offl/EIGENVALUES-AND-EIGENVECTORS/assets/147140026/0bccbb65-44eb-46f2-89e5-86da07da93db)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
