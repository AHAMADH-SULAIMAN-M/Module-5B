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

```python
import numpy as np 

rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter the array elements row-wise:")
data = []
for i in range(rows):
    row = list(map(int, input().split()))
    data.append(row)

arr = np.array(data)

print("Enter the new column elements:")
new_col = np.array([int(input()) for _ in range(rows)])

arr_deleted = np.delete(arr, 1, axis=1)

updated_arr = np.insert(arr_deleted, 1, new_col, axis=1)


print("\nOriginal Array:")
print(arr)

print("\nUpdated Array After Replacing Second Column:")
print(updated_arr)

```

## Output


<img width="815" height="596" alt="image" src="https://github.com/user-attachments/assets/6fc2ef3e-ff7e-406b-92ff-f7f22e07bf9d" />

## Result

The python program that deletes the second  column from a given 2d Array and inserts a new column at the same position
