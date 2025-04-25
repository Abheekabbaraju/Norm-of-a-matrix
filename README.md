# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Import the NumPy module to access matrix and norm functions.
2.Define the matrix using np.array().
3.Use np.linalg.norm() to compute the desired norm (default is Frobenius norm).
4.Display the norm using a print statement.
5.End the program.
	
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
```


# 2-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```

# Infinity Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-25 153330](https://github.com/user-attachments/assets/faf78278-277a-4fe1-8d44-623a1548dcca)


### 2-Norm of a Matrix

![Screenshot 2025-04-25 153339](https://github.com/user-attachments/assets/22b24e55-e15d-46c8-a64b-e64e2b3c0ded)

### Infinity Norm of a Matrix

![Screenshot 2025-04-25 153348](https://github.com/user-attachments/assets/16133dc3-3fa2-4f68-b5f6-dc35498d792a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
