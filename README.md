# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212223240188
# Developed By: Yuvan M
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))



```
## Output:
### 1-Norm of a Matrix
![norm](https://github.com/Yuvan291205/Norm-of-a-matrix/assets/138849170/5d831148-b3b4-4195-99d1-039dc1424660)


### 2-Norm of a Matrix
![2norm](https://github.com/Yuvan291205/Norm-of-a-matrix/assets/138849170/3eed8bf6-9b45-4e66-9d64-ec3dc4e879d7)


### Infinity Norm of a Matrix
![3norm](https://github.com/Yuvan291205/Norm-of-a-matrix/assets/138849170/61d587c4-1f91-43e4-8579-8816f3a41545)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
