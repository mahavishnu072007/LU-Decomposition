# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Input the matrix
2. Initialize L and U matrices
3. Perform decomposition
4. Output the results

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:MAHA VISHNU S 
RegisterNumber: 25018250
'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
<img width="1206" height="756" alt="image" src="https://github.com/user-attachments/assets/9bf8fba3-0b2e-4828-8a3d-3eb3a9098276" />

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: MAHA VISHNU S
RegisterNumber: 25018250
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
```
<img width="1206" height="717" alt="image" src="https://github.com/user-attachments/assets/1da67644-c871-42f4-a9e2-ba6ae65e126d" />


## Output:
<img width="1227" height="562" alt="image" src="https://github.com/user-attachments/assets/63b61195-2c61-4c36-8b2e-5f7656bffd0c" />
<img width="1227" height="292" alt="image" src="https://github.com/user-attachments/assets/b63ed366-96e3-47c2-afab-ecc93189ecd0" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

