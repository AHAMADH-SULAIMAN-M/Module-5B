# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```python
'import pandas as pd   

student_data1 = {
    'id': [1, 2, 3],
    'name': ['Alice', 'Bob', 'Charlie']
}
df1 = pd.DataFrame(student_data1)

student_data2 = {
    'id': [4, 5, 6],
    'name': ['David', 'Emma', 'Frank']
}
df2 = pd.DataFrame(student_data2)


combined_df = pd.concat([df1, df2], axis=0)
print(combined_df)
```
## Output

<img width="822" height="394" alt="image" src="https://github.com/user-attachments/assets/65d539fa-b320-4c99-8115-92389a7f7d4f" />

## Result
The python program using pandas to join the two Dataframes along rows and assign it to the new dataframe is executed Successfully and verified
