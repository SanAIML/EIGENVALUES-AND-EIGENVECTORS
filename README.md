# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: input the array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the values and vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:SANCHITA SANDEEP 
#RegisterNumber:212224240142
import numpy as np
a = np.array([[4,2],[2,4]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format (values,vectors))
```

## Output:
![Screenshot 2025-03-25 085244](https://github.com/user-attachments/assets/944eb4aa-26dc-47fe-9632-795ab1632148)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
