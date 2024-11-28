# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy which has built-in function for matrix operation
### Step 2: Represent the matrix as a 2D numpy array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))

```
## Output:
![Screenshot 2024-11-27 133053](https://github.com/user-attachments/assets/bae9922f-b467-46a8-9d84-106b5b78417c)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
