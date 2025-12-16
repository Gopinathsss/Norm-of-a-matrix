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
# Register No:25012981
# Developed By:GOPINATH S
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(f"{norm1:.2f}")


# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,2)
print(f"{norm1:.2f}")



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
normal=np.linalg.norm(a,np.inf)
print(f"{normal:.2f}")



```
## Output:
### 1-Norm of a Matrix
<br<img width="1365" height="766" alt="image" src="https://github.com/user-attachments/assets/b096d420-5bc1-49bd-adc6-f92f970082b4" />
>
<br>
<br>

### 2-Norm of a Matrix
<br>
<br><img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/9ed7fa65-3c4b-42a0-b6e5-cf9dd3d5f15a" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="1362" height="763" alt="image" src="https://github.com/user-attachments/assets/ea87a9f5-d769-4ef7-980e-55e0be87cbe7" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
