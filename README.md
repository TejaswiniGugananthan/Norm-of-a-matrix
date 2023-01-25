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
# Register No:22004187
# Developed By:Tejaswini.G
# 1-Norm of a Matrix:
```python
###Program to find 1-norm of a matrix.
###Developed by: Tejaswini.G
###RegisterNumber:22004187
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix:
'''
Program to find 2-norm of a matrix:
Developed by: Tejaswini.G
RegisterNumber: 22004187
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix:
'''
Program to find infinity norm of a matrix.
Developed by: Tejaswini.G
RegisterNumber: 22004187

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
<img width="270" alt="image" src="https://user-images.githubusercontent.com/121222763/214521461-8bb47781-0978-4fdc-8c6d-6df05a77ebd0.png">


### 2-Norm of a Matrix
<img width="238" alt="image" src="https://user-images.githubusercontent.com/121222763/214521560-5b559c50-5a16-4ad7-9f70-1ad877f75543.png">


### Infinity Norm of a Matrix
<img width="275" alt="image" src="https://user-images.githubusercontent.com/121222763/214521641-2525680b-e7b8-46f4-9028-bdb8effb2396.png">


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
