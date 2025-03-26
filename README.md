# 📜 Python Sets - A Comprehensive Guide

This repository contains a Jupyter Notebook (`Set.ipynb`) that demonstrates various operations on Python sets, including adding, removing, and performing set operations like union, intersection, difference, and symmetric difference.

## 📌 Key Concepts
✅ **Unordered Collection** – Sets do not maintain a specific order.
✅ **Unique Elements** – Duplicate values are automatically removed.
✅ **Mutable** – Elements can be added or removed, but sets themselves are mutable.
✅ **Efficient Membership Testing** – Checking if an element exists is optimized.

## 🚀 Features
- Creating and accessing set elements
- Adding and removing items
- Performing union, intersection, and difference operations
- Utilizing operators like `|`, `&`, `-`, and `^` for set manipulations
- Handling boolean and numeric overlaps

## 🔧 Installation & Usage
To use the notebook, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/aliikhan1323/Sets--Python.git
   cd python-sets
   ```
2. Install Jupyter Notebook (if not already installed):
   ```bash
   pip install notebook
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Set.ipynb
   ```

## 🖥️ Code Example
```python
# Define a set
fruits = {"apple", "banana", "mango", "orange"}
print(fruits)

# Union of sets
set1 = {1, 2, 3}
set2 = {3, 4, 5}
print(set1 | set2)  # Output: {1, 2, 3, 4, 5}
```

## 📊 Expected Output
```
{'apple', 'banana', 'mango', 'orange'}
{1, 2, 3, 4, 5}
```

## 💡 Use Cases
🔹 Removing duplicates from a dataset.
🔹 Performing fast lookups in large datasets.
🔹 Set operations in mathematical computations.

