# 📊 Python for Data Handling – NumPy, Pandas, Matplotlib

Data is at the heart of AI and machine learning. This guide introduces you to three essential libraries used for **data analysis, manipulation, and visualization** in Python.

---

## 🧮 1. NumPy – Numerical Python

NumPy allows you to work with arrays and perform high-speed mathematical operations.

### 🧪 Example:

```python
import numpy as np

arr = np.array([1, 2, 3, 4])
print(arr * 2)  # Output: [2 4 6 8]

# 2D array (matrix)
matrix = np.array([[1, 2], [3, 4]])
print(matrix.shape)  # Output: (2, 2)
```

---

## 🗃️ 2. Pandas – DataFrames and CSVs

Pandas is used for handling **structured data** like tables, spreadsheets, and CSV files.

### 🧪 Example:

```python
import pandas as pd

# Read a CSV file
data = pd.read_csv("data.csv")
print(data.head())  # Print first 5 rows

# Create a DataFrame from a dictionary
df = pd.DataFrame({"Name": ["Alice", "Bob"], "Score": [85, 90]})
print(df)
```

---

## 📊 3. Matplotlib – Plotting and Visualization

Use this to create charts and graphs to understand your data better.

### 🧪 Example:

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.plot(x, y)
plt.title("Simple Line Plot")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()
```

---

## 📌 When to Use These:

| Task                              | Library    |
| --------------------------------- | ---------- |
| Fast math & arrays                | NumPy      |
| Working with CSVs or Excel        | Pandas     |
| Visualizing trends or comparisons | Matplotlib |

---

## ✅ Practice Tip:

Try this workflow:

1. Use **Pandas** to load and clean your dataset
2. Use **NumPy** to apply any calculations
3. Use **Matplotlib** to visualize your results

This is the standard process in almost every AI and ML project.

---


