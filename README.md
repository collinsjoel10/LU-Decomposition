# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement
2. from scipy package import lu()
3. get input from user and pass it as an array
4. print l and u matrix

## Program:
(i) To find the L and U matrix
```
import numpy as np   #form numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: joel p
RegisterNumber: 22008934
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: joel p
RegisterNumber: 22008934
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![output](ludecomposition.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

