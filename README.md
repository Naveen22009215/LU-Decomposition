# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. in the first step to find lu decomposition we using import numpy as np
2. next we using scipy.linalg for import
3. next we settimg the variable name 
4. finally printing the value

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:P NAVEEN KUMAR 
RegisterNumber:22009215

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:P NAVEEN KUMAR 
RegisterNumber:22009215

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),b)
print (x)
*/
```

## Output:
![ludecomposition](/op1.png)


![ludecomposition](/op2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

