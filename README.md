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
Developed by: Rajkumar G
RegisterNumber: 23003498
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
Developed by: Rajkumar G
RegisterNumber: 23003498
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
![Screenshot 2023-12-29 110254](https://github.com/Rajkumar28072005/LU-Decomposition/assets/144980101/28299aa3-0870-42dd-8c7f-795894b21de3)

![Screenshot 2023-12-29 110441](https://github.com/Rajkumar28072005/LU-Decomposition/assets/144980101/04c94175-40e1-4a0b-8c73-0228a3102ea7)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

