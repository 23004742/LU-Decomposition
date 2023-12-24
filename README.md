# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.first use the import 
2.second use the numpy operatore
3.thrid i use the print statment 
4.i got the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix. 
*/
```
Program to find L and U matrix using LU decomposition.
Developed by:L.yagnesh kumar reddy
RegisterNumber:23004742
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:L.yagnesh kumar reddy 
RegisterNumber:23004742 
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np 
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)

/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:

![Screenshot 2023-12-24 200240](https://github.com/23004742/LU-Decomposition/assets/150319318/37b57487-6e6b-4fe1-8ec9-cb7d93d6c7cd)

![Screenshot 2023-12-24 200259](https://github.com/23004742/LU-Decomposition/assets/150319318/8636a503-ef38-440c-a16b-34f26dd5e604)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

