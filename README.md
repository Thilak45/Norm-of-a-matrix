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
```
# 1-Norm of a matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname:TILAK VELLACHI
RegisterNumber: 23009564
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Thilak45/Norm-of-a-matrix/assets/138849161/59a9245f-cf87-4a7c-aa10-956370828470)


### 2-Norm of a Matrix
![image](https://github.com/Thilak45/Norm-of-a-matrix/assets/138849161/72dd5980-b65e-4015-b826-9915ac92f13e)



### Infinity Norm of a Matrix
![image](https://github.com/Thilak45/Norm-of-a-matrix/assets/138849161/c873886a-74ed-4f0d-a99e-64ea6081cb1e)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
