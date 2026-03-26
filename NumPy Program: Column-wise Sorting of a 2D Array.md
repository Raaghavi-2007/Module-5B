# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
array=np.array(eval(input())
print("Original array:",array)
result=np.sort(array,axis=0)
print("sorted array:",result)
```
## Output
<img width="381" height="158" alt="image" src="https://github.com/user-attachments/assets/a6014c1a-22b8-4398-9979-65607b1ff36b" />

## Result
Thus, the program is successfully executed.
