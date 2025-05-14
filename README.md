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
# Register No: TAMIL PAVALAN M
# Developed By: 212223110058
# 1-Norm of a Matrix

import numpy as np
mat=np.array (eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: TAMIL PAVALAN M
RegisterNumber:212223110058
'''
import numpy as np
mat=np.array (eval (input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print (Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/29dd71f7-095d-4575-8ea4-fcbdf4244de4)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/1cd4f250-dfef-449e-8ab6-538942184b67)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/a5a58515-ca80-4c96-9a66-3d2d753853cd)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
