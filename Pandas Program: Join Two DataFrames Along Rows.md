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
```
import pandas as pd
a=eval(input())
b=eval(input())
d1=pd.DataFrame(a)
d2=pd.DataFrame(b)
print("Join first two said dataframes along rows:")
d=pd.concat([d1,d2])
print(d)
```

## Output
<img width="1000" height="307" alt="image" src="https://github.com/user-attachments/assets/d24e4021-395a-42e0-ad8f-d0b09079e3e4" />


## Result
Thus, the given program has been executed successfully and the two DataFrames are joined along rows using Pandas.
