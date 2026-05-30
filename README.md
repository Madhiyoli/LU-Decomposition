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
'''Program to find L and U matrix using LU decomposition.
Developed by: Madhiyoli.C
RegisterNumber: 212225230157
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```Program to solve a matrix using LU decomposition.
Developed by: Madhiyoli.C
RegisterNumber: 212225230157

import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```
## Output:
<img width="1250" height="506" alt="Screenshot 2026-05-30 230925" src="https://github.com/user-attachments/assets/e94280c9-28b9-4cf5-856c-0de6aac39512" />

<img width="1125" height="203" alt="image" src="https://github.com/user-attachments/assets/0954c584-a731-462a-9982-0b3e25c9e61f" />

![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

