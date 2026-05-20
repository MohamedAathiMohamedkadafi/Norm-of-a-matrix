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
# Register No:212225040246
# Developed By:MOHAMED AATHIL M
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="596" height="202" alt="593703557-e84f4510-90e9-4eb7-b674-fdd9177be990" src="https://github.com/user-attachments/assets/d443da20-9ce0-4b64-8557-84e76faa0f0b" />

### 2-Norm of a Matrix
<img width="557" height="252" alt="593703571-3379fe7f-e07d-493b-bf1d-a0c62f99faa2" src="https://github.com/user-attachments/assets/dcf01806-03fe-4142-912b-a733581dd13c" />


### Infinity Norm of a Matrix
<img width="570" height="200" alt="593703586-ae356db4-be20-4fc4-aff2-f670f56d1f67" src="https://github.com/user-attachments/assets/8559c4e8-b46c-454f-bc00-96fb019706ca" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
