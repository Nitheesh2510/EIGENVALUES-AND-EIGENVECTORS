# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation

### Step 2: Prepare the lists from each equations and assign in np.array()

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: End the program


## Program:
```
Developed by:Nitheesh Kumar B
re no:2122224230189
import numpy as np
A = np.array([[2,2],[1,3]])
B,C = np.linalg.eig(A)
print(f"Eigen values are {B} and Eigen Vectors are {C}")
```
## Output:





![Screenshot 2025-03-28 143036](https://github.com/user-attachments/assets/429443b8-42d7-45c4-8ba1-fcaa2f59c63e)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
