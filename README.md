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
# Register No:212225230313		
# Developed By:Yuuvasri R
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="818" height="393" alt="Screenshot 2026-02-26 141507" src="https://github.com/user-attachments/assets/d884adc1-1b2a-451c-b897-3c1ce2f06eb7" />
<br>

### 2-Norm of a Matrix
<img width="1079" height="255" alt="Screenshot 2026-02-12 133737" src="https://github.com/user-attachments/assets/b88e4b18-d91f-45c4-b21b-3db10e110431" />
<br>

### Infinity Norm of a Matrix
<img width="908" height="249" alt="Screenshot 2026-02-12 133747" src="https://github.com/user-attachments/assets/7ce68d63-8c73-4e62-b5e2-6c4bea800531" />
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.



















.




















.





















.
.




























.





























.
