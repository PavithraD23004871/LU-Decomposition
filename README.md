# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input fron the user
4. print result

## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: pavitra
RegisterNumber: 23004871
'''

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: pavitra
RegisterNumber: 23004871
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

## Output:
![image](https://github.com/PavithraD23004871/LU-Decomposition/assets/138955967/a1722dc7-5563-4441-8d22-624b8c8ce572)
![image](https://github.com/PavithraD23004871/LU-Decomposition/assets/138955967/6af43c43-d29b-4232-8628-0abd3273945d)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

