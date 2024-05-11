# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Matrix Initialization
### Step 2: 
Eigenvalue and Eigenvector Calculation:
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
The code computes the eigenvalues and eigenvectors of the given 2x2 matrix 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PRADEEP V (or) Balaji
#RegisterNumber:212223240119
import numpy
a=[[2,2],[1,3]]
w,v=numpy.linalg.eig(a)
print("Eigen values are",w,"and Eigen Vectors are",v)
```

## Output:
![Screenshot 2023-12-24 101300](https://github.com/velupradeep/EIGENVALUES-AND-EIGENVECTORS/assets/150329341/c7e11a7e-d9be-4631-b306-f88404d61dd0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
