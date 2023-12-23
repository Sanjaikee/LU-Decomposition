# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy
2. from scipy.linlag import lu,lu_factor,lu,solve.
3. solve using scipy.linlag(variable)
4. Print the output 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: R. Sanjana
RegisterNumber: 23008112
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: R. Sanjana
RegisterNumber: 23008112
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```

## Output:
![lu decomposition]()

![Screenshot 2023-12-23 121355](https://github.com/23008112/LU-Decomposition/assets/138972470/e63f5a84-f8a2-4237-8c84-abb12803e03a)

![Screenshot 2023-12-23 121415](https://github.com/23008112/LU-Decomposition/assets/138972470/1263360c-f60e-4243-b736-1ace1a3a29f0)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

