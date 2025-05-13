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
# Register No:212224230302
# Developed By:P.VIGNESH
```Python
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
normmat = "{:.2f}".format(ans)
print(normmat)


# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
normmat = "{:.2f}".format(ans)
print(normmat)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
normmat = "{:.2f}".format(ans)
print(normmat)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/44b0fd29-80e2-4030-91ba-cc4fc20fc6ea)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/396c58b9-8b27-4e0c-9a8a-0dd82bc5c305)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/e3567d70-188f-4dfa-bbfb-47607dcc0c9b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
