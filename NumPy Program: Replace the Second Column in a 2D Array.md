# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np
x=np.array(eval(input())
n=np.array(eval(input())
removed=np.delete(x,1,axis=1)
print("Original array")
print(x)
print("array after deletion")
print(removed)
print("array after insertion")
print(insert)
```
## Output
<img width="279" height="240" alt="image" src="https://github.com/user-attachments/assets/17b9cfdf-8f4a-4e3e-87cf-47ba7cbbed99" />

## Result
Thus, the program is successfully executed.
