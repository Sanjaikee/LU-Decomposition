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
Developed by: Sanjai S
RegisterNumber: 23003393
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
Developed by: Sanjai S
RegisterNumber: 23003393
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```

## Output:
![Screenshot 2023-12-23 091832](https://github.com/Sanjaikee/LU-Decomposition/assets/150231888/466be5e1-1328-40fc-ae48-b4a70974ee3a)
![Screenshot 2023-12-23 091851](https://github.com/Sanjaikee/LU-Decomposition/assets/150231888/c8ddbeb6-21e2-4298-a067-99593410a2a9)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

