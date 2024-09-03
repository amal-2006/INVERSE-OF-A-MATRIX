## DATE:
## EX 3 - INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program

## Program:
```



#Program to find the inverse of a matrix.
#Developed by: AMALJOSH MAADHAV J
#RegisterNumber: 212223230012


import numpy as np
matrix = np.array([[1, 0, 3], [-1, 2, -2], [2, 3, -1]])
B = np.linalg.inv(matrix)
print(B)





```
## Output:
![image](https://github.com/user-attachments/assets/bafc6ec0-972f-42a9-b9d9-7f4ae59d87af)

## Result:
Thus the inverse of given matrix is successfully solved using python program

