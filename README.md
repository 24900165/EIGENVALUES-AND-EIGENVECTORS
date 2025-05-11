# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the NumPy module using import numpy as np to perform matrix computations 
### Step 2: 
Define the square matrix using np.array().
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Store the Eigenvalues and Eigenvectors returned by the function.
### Step 5:
Display the Eigenvalues and Eigenvectors using the print() function.
### Step 6:
End the program.

## Program:
```
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eig_values,eig_vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))
```

## Output:
![alt text](<Screenshot 2025-05-11 180816.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
