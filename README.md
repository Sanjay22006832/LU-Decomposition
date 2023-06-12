# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy as np and from scipy import lu

2.Get the input of array from the user

3.solve P,L,U and print the values

4.End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: M Sanjay
RegisterNumber: 212222240090
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
p,l,u=lu(arr)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: M Sanjay 
RegisterNumber: 212222240090
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array(eval(input()))
b=np.array(eval(input()))
lu,p=lu_factor(arr)
res=lu_solve([lu,p],b)
print(res)
```

## Output:
![Screenshot 2023-06-12 204444](https://github.com/Sanjay22006832/LU-Decomposition/assets/119830477/1bd7d5b2-c87a-43b6-9fcb-da3764affc09)

![Screenshot 2023-06-12 204455](https://github.com/Sanjay22006832/LU-Decomposition/assets/119830477/be796508-016b-4b69-a527-cf23016e2b73)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

