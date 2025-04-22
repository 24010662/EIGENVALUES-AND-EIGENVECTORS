# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import the NumPy library using 'import numpy as np'.

### Step 2: Define the matrix using np.array().

### Step 3: Using np.linalg.eig(), compute the eigenvalues and eigenvectors.

### Step 4: Display the eigenvalues and eigenvectors using print().

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: vutukuri sai Kumar Reddy 
#RegisterNumber:212224230307

import numpy as np
a = np.array([[-2,2,-3], [2,1,-6],[-1,-2,0]])
eig_value,eig_vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))
```

## Output:
![Screenshot 2025-04-22 081543](https://github.com/user-attachments/assets/30de55a8-de87-49e2-8521-11fa027b3304)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
