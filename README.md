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
# Register No:26007691
# Developed By:Gopinath n
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Gopinath n
RegisterNumber:26007691 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))


```
## Output:
### 1-Norm of a Matrix


<img width="1271" height="206" alt="image" src="https://github.com/user-attachments/assets/ec1968f1-dcbb-42f9-830a-4d95647df20f" />

### 2-Norm of a Matrix

<img width="1285" height="257" alt="image" src="https://github.com/user-attachments/assets/88a595ff-1890-4809-95cb-e8b476d82568" />


### Infinity Norm of a Matrix

<img width="1170" height="231" alt="image" src="https://github.com/user-attachments/assets/e90d07dc-4889-4298-b026-dbd1448f635f" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
