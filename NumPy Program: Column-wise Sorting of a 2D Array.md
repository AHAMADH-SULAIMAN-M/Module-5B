<img width="827" height="494" alt="image" src="https://github.com/user-attachments/assets/a114ab61-e598-4de1-a759-bf4a01030fcd" /># NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```python
import numpy as np  
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter the elements row-wise:")
data = []
for i in range(rows):
    row = list(map(int, input().split()))
    data.append(row)

arr = np.array(data)

sorted_arr = np.sort(arr, axis=0)

print("\nOriginal Array:")
print(arr)

print("\nColumn-wise Sorted Array:")
print(sorted_arr)

```

## Output
<img width="827" height="494" alt="image" src="https://github.com/user-attachments/assets/adfadb0f-ffcc-4279-bd6f-3bdee0802ada" />

## Result
The python program that elements in each column  of a given 2d array is ascending order is executed Successfully and verified.
