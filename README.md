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
# Register No:212223240023
# Developed By:Daniel C
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
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
![image](https://github.com/Daniel-christal/Norm-of-a-matrix/assets/145742847/dc4c2414-2848-4671-922b-8c42c876bc66)

### 2-Norm of a Matrix
![image](https://github.com/Daniel-christal/Norm-of-a-matrix/assets/145742847/a5ad857b-dc0d-4088-8b03-61bb51557265)
 
### Infinity Norm of a Matrix 
![image](https://github.com/Daniel-christal/Norm-of-a-matrix/assets/145742847/ae6cd920-3ce0-4369-a1df-d73c126a292a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
