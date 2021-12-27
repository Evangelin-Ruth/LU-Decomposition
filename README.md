# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 1. To Find L and U matrices with LU Decomposition
Step 1: Get the matrix from the user.

Step 2: Using "from scipy.linalg import lu" to import scipy (LU) module.

Step 3: Using "L,U=lu(a)" we can get the matrix of L and U.

Step 4: Print the result matrices (L and U Matrices).

Step 5: End of the Program.


### 2. To Find X matrix with LU Decomposition
Step 1: Get the matrix from the user.

Step 2: Using "from scipy.linalg import lu_factor,lu_solve" to import scipy module for factorization and solving X.

Step 3: Using "lu,piv=lu_factor(a)" 

Step 4: 

Step 5: End of the Program.


## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Evangelin.S
RegisterNumber: 21500561
*/
```
```
To print L and U matrix:

import numpy as np
import scipy
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)
print (L)
print(U)

To print X matrix(Solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)
```

## Output:
###1.To Find L and U matrices with LU Decomposition
![L and U matrix 1](https://user-images.githubusercontent.com/94219798/147453932-9ebfcbb0-fa66-4fc0-a691-527e47662df1.JPG)
###2.To Finf X matrix with LU Decomposition
![L and U matrix 2](https://user-images.githubusercontent.com/94219798/147453957-a57212da-c74c-4b2a-b9da-753e1738d664.JPG)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

