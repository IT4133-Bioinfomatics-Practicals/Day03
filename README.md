# Day 03: Lists, Arrays & NumPy 📚

## Overview

Comprehensive practical guide covering Python lists, NumPy arrays, and multi-dimensional data structures used in computational biology.

---

## 📋 List & Array.ipynb

### Topics Covered:

- **List Creation** ✅

  - Multiple data types in single list (strings, numbers, floats)
  - List properties: `len()`, `type()`

- **List Operations** 🔧
  - Indexing: Access elements by position
  - `append()` - Add elements to end
  - `pop()` - Remove last element
  - `clear()` - Remove all elements
  - `copy()` - Create list copy
  - `count()` - Count occurrences
  - `extend()` - Merge lists
  - `index()` - Find element position
  - `insert()` - Add element at specific position
  - `remove()` - Remove specific element
  - `sort()` - Sort list in ascending order

---

## 🔢 Array.ipynb

### Topics Covered:

- **NumPy Array Creation** 📊

  - `np.linspace()` - Create evenly spaced values
  - `np.zeros()` - Create array of zeros
  - `np.ones()` - Create array of ones
  - `np.random.rand()` - Create array of random values

- **1D Array Operations** 1️⃣

  - Element access by index
  - Slicing: `arr[start:end]`
  - Negative indexing: `arr[-2:]`
  - Range calculation (max - min)

- **2D Array Operations** 2️⃣
  - Creating 2D arrays from lists
  - Accessing specific elements: `arr[row, col]`
  - Row and column extraction
  - Slicing multi-dimensional arrays: `arr[0:2, 1:3]`
  - Computing range of sub-arrays

---

## 🎯 Numpy_Library.ipynb

### Topics Covered:

- **Array Dimensions** 📐

  - **1D Arrays**: Single row/column of values
  - **2D Arrays**: Rows and columns (matrices)
  - **3D Arrays**: Stacked 2D arrays
  - **4D Arrays**: Multiple stacked 3D arrays

- **NumPy Array Construction** 🏗️
  - Creating arrays from Python lists
  - Using list comprehensions for multi-dimensional structures
  - Converting lists to NumPy arrays

---

## 🎓 Key Concepts

| Feature            | Purpose                       | Example               |
| ------------------ | ----------------------------- | --------------------- |
| **Lists**          | Flexible, mutable collections | `['apple', 1, 2.45]`  |
| **NumPy Arrays**   | Fast numerical computations   | `np.array([1, 2, 3])` |
| **1D Array**       | Single dimension data         | `[1, 2, 3, 4, 5]`     |
| **2D Array**       | Matrix-like data              | `[[1,2,3], [4,5,6]]`  |
| **Multi-D Arrays** | Complex data structures       | Tensors for ML/BI     |

---

## 💡 Quick Tips

✨ Use **Lists** for: General data storage, mixed types, frequent modifications  
⚡ Use **NumPy Arrays** for: Scientific computing, matrix operations, large datasets  
🧬 Use **Multi-D Arrays** for: Genomic data, image processing, computational biology

---

## 📝 Notes

These practicals form the foundation for advanced bioinformatics data analysis using Python. Master these concepts before moving to data analysis libraries like Pandas and SciPy.
