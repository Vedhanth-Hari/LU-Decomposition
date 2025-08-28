# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

 step1: find the 1 and u matirx by using numpy and linalg from scipy

step2: print the 1 matrix and u matirx

step3: find the lu decomposition by using numpy and lu_factor and lu_solve

step4: print the the following matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: H.Vedhanth
RegisterNumber: 212224240181
*/

import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: H.Vedhanth
RegisterNumber: 212224240181
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)

```

## Output:
<img width="1286" height="971" alt="image" src="https://github.com/user-attachments/assets/bc93f177-9fb2-4194-a662-ad888d441fd1" />

<img width="1224" height="857" alt="Screenshot 2025-08-28 094313" src="https://github.com/user-attachments/assets/d20affc4-8d31-4004-acaf-1ea42a7d33df" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

