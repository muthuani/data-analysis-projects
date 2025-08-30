# 📘 NumPy Basics

## 🔹 Introduction
- NumPy (Numerical Python) is a powerful Python library for numerical computing.  
- Provides support for **multi-dimensional arrays** and **mathematical operations**.  
- Faster and more efficient than Python lists for numerical data.  

---

## 🔹 NumPy Array
- Core object is `ndarray` (n-dimensional array).  
- Arrays can be **1D, 2D, or multi-dimensional**.  
- Homogeneous: all elements must be of the same data type.  

---


## 🔹 Array Attributes
- **`ndim`** → Number of dimensions.  
- **`shape`** → Dimensions (rows, columns).  
- **`size`** → Total number of elements.  
- **`dtype`** → Data type of elements.  
- **`itemsize`** → Size of each element (in bytes).  

---

## 🔹 Array Creation
- Creating arrays from Python lists.  
- Predefined arrays (zeros, ones, empty, identity).  
- Ranges (arange, linspace).  
- Random number generation.  

---

## 🔹 Reshaping and Manipulation
- Reshape, flatten, ravel.  
- Stacking (horizontal, vertical).  
- Splitting arrays.  

---

## 🔹 Random Module
- Random numbers from uniform and normal distributions.  
- Random integers.  
- Shuffling and permutation.  

---

## 🔹 Indexing and Slicing
- Accessing elements using indices.  
- Negative indexing for reverse access.  
- Slicing for extracting sub-arrays.  
- Boolean indexing and fancy indexing.  

---

## 🔹 Array Operations
- Element-wise arithmetic operations.  
- Comparison operators.  
- Universal functions (ufuncs) such as trigonometric, exponential, logarithmic, square root.  

---

## 🔹 Matrix Operations
- Addition, subtraction, multiplication.  
- Dot product and matrix multiplication.  
- Transpose, inverse, determinant.  

---

## 🔹 Scalars
- A **scalar** is a single numerical value.  
- In NumPy, scalars are treated as **0-dimensional arrays**.  
- Array–scalar operations are supported through **broadcasting**.  
- Example: adding or multiplying a scalar to an array applies the operation to every element.  

---

## 🔹 Filters
- Filtering means **selecting elements** from an array based on conditions.  
- Done using **Boolean masks** (arrays of True/False values).  
- Steps:  
  1. Apply condition → generates Boolean array.  
  2. Use Boolean array to extract matching values.  
- Supports logical operations (`&`, `|`, `~`) for complex conditions.  
- Used in data analysis, cleaning, and conditional selection.  

---

## 🔹 Broadcasting
- Allows operations on arrays of different shapes.  
- Smaller array is “broadcasted” to match the shape of the larger array.  

---

## 🔹 Linear Algebra
- Matrix multiplication.  
- Determinant, rank, trace.  
- Eigenvalues and eigenvectors.  
- Solving linear equations.  

---

## 🔹 Useful Functions
- Statistical functions (sum, mean, median, std, var).  
- Aggregations (min, max, argmin, argmax).  
- Sorting and searching functions.  
- Unique values and counts.  

---