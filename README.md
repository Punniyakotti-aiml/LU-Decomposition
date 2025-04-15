# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 step1:
find the 1 and u matirx by using numpy and linalg from scipy

step2:
print the 1 matrix and u matirx

step3:
find the lu decomposition by using numpy and lu_factor and lu_solve

step4:
print the the following matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Punniyakotti.M
RegisterNumber: 212224240122
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Punniyakotti.M
RegisterNumber":212224240122 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
 ![Screenshot (36)](https://github.com/user-attachments/assets/88ff91a0-3499-4a72-a1fe-c35f84f7a228)

![Screenshot (37)](https://github.com/user-attachments/assets/219129a1-f928-4c4d-8df4-580ca6a336d9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

