<img width="1266" height="906" alt="image" src="https://github.com/user-attachments/assets/ddaad2c1-93bf-417b-97fd-24bdc2e43b8c" /># EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:

#program to find the eigenvalues and eigen vectors

#done by: DHANVARSINI.S

#reg no: 212225240032

import numpy as np

a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])

Values,vectors= np.linalg.eig(a)

print('Eigen values are {} and Eigen Vectors are {}'.format(Values,vectors))


## Output:
<img width="1266" height="906" alt="Screenshot 2026-02-04 190239" src="https://github.com/user-attachments/assets/0a2caf1b-ef98-432c-897e-3cd78c36bb7d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
