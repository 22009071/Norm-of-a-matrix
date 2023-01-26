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
# Register No:kabilan T
# Developed By:2009071
# 1-Norm of a Matrix
import numpy as np

a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
print("{:.2f}".format(ans))




# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: R.KARTHIKEYAN
RegisterNumber:22002525 

import numpy as np

a= np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))





# Infinity Norm of a Matrix

import numpy as np

a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))






```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/120206067/214588825-8d0272e7-0b0e-4d66-9e7c-3cceef8ac1cb.png)
![](1norm.png)

### 2-Norm of a Matrix
![](2normScreenshot_20230125_074521.png.png)

### Infinity Norm of a Matrix
![]("C:\Users\kabilan\Pictures\Screenshots\Screenshot_20230125_011744.png".png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
