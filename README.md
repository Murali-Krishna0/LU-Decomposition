# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Murali Krishna S
RegisterNumber: 212223230129
from scipy.linalg import lu
a = eval(input())
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Murali Krishna S
RegisterNumber: 212223230129
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![image](https://github.com/Murali-Krishna0/LU-Decomposition/assets/149054535/0d4712a2-3787-4127-be75-3bbd2d038753)
![image](https://github.com/Murali-Krishna0/LU-Decomposition/assets/149054535/5ad369b9-6ccf-4af1-9270-e6b0b35d20a1)
![image](https://github.com/Murali-Krishna0/LU-Decomposition/assets/149054535/f832f381-c2d5-4b81-a405-b463387c62f5)
![image](https://github.com/Murali-Krishna0/LU-Decomposition/assets/149054535/7fce89a6-6f98-4855-ad3b-9e4498be0c5f)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

