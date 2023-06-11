# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
arrange the given matrix in np.array command
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
run the program and get the output
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: rohith r
#RegisterNumber: 212222230121
import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![209474822-aeed20d5-5b09-49f7-8baa-79ce4ad3d7a9](https://github.com/Rohithravi333/EIGENVALUES-AND-EIGENVECTORS/assets/119394126/cf6c4a83-8a67-459a-9122-e6cd90b38386)
![209474831-7828be1d-bf53-40fb-ad9c-961b6621e1d4](https://github.com/Rohithravi333/EIGENVALUES-AND-EIGENVECTORS/assets/119394126/6eefb2e0-0843-45f1-b55e-7fd20881d4a8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
