# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. us ethe concept of Lu decomposition
3. first find l and u matrix
4. Then find LU matrix
5. Stop the program
   

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Dhandeeswaran selvakumar
RegisterNumber: 23006838
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Dhandeeswaran selvakumar
RegisterNumber: 23006838
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![output](https://github.com/dhandeeswaran2005/LU-Decomposition/assets/147139188/ca346b01-a199-4667-ba9f-8fabda8de95e)
![output1](https://github.com/dhandeeswaran2005/LU-Decomposition/assets/147139188/f95ae919-a0dc-40db-952d-464c7044234f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

