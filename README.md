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
# program to find the 1-norm, 2-norm and infinity norm of the matrix
# Register No: MOHANKUMAR.S
# Developed By:23050020014

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
Norm_of_matrix = "{:.2f}". format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}". format(ans)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-24 190921](https://github.com/MohanKumar755/Norm-of-a-matrix/assets/146155007/8a1bcb7c-13f8-48d8-b272-ec620bc83801)

[[-1, 3], [3, 4], [1, 7]]

14.00
### 2-Norm of a Matrix
![Screenshot 2024-05-24 192654](https://github.com/MohanKumar755/Norm-of-a-matrix/assets/146155007/e64a2e2f-6b2c-4a71-af1e-1955e3cba7a2)

[[1,2], [3,4]]

5.46
### Infinity Norm of a Matrix
![Screenshot 2024-05-24 192918](https://github.com/MohanKumar755/Norm-of-a-matrix/assets/146155007/42e05959-31d7-4daf-b57e-5b763cfa5d93)

[[-1,3], [3,-4], [1,7]]
8.00
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
