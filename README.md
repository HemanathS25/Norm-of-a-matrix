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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
# Type your code here




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>

![Screenshot 2024-12-01 200114](https://github.com/user-attachments/assets/5983b312-04c8-4278-81bc-136d41326495)
<br>
### 2-Norm of a Matrix
<br>
<br>

![Screenshot 2024-12-01 200129](https://github.com/user-attachments/assets/bd597f5f-e79e-4024-bc60-130f75711b38)
<br>
### Infinity Norm of a Matrix
<br>
<br>

![Screenshot 2024-12-01 200144](https://github.com/user-attachments/assets/2c650289-7703-4b0e-bc76-942790bc5c1a)
<br>
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
