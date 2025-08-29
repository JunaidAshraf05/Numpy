# NumPy Learning Repository

This repository is a **learning resource** to practice and master **NumPy**, Python’s core library for scientific and numerical computing.
It contains Jupyter notebooks with **step-by-step examples**, exercises, and explanations for beginners.

---

## 📂 Repository Structure

* **`1.ipynb` → Basics of NumPy**

  * Installing & importing NumPy
  * Creating arrays: `array()`, `arange()`, `linspace()`
  * Array attributes: `.shape`, `.ndim`, `.dtype`, `.size`
  * Basic operations: addition, subtraction, multiplication, division

* **`2.ipynb` → Indexing & Array Manipulation**

  * Indexing & slicing (`arr[1:5]`, `arr[:, 0]`)
  * Reshaping arrays with `.reshape()`
  * Stacking arrays: `hstack()`, `vstack()`
  * Splitting arrays: `hsplit()`, `vsplit()`
  * Broadcasting rules and examples

* **`3.ipynb` → Mathematical & Advanced Functions**

  * Universal functions (e.g. `np.sqrt()`, `np.exp()`, `np.log()`)
  * Aggregations: `sum()`, `mean()`, `std()`, `var()`
  * Matrix operations: `dot()`, `matmul()`, `linalg.inv()`, `linalg.eig()`
  * Random numbers: `np.random.rand()`, `np.random.randint()`

---

## ⚙️ Requirements

* Python 3.7+
* [NumPy](https://numpy.org/)
* [Jupyter Notebook](https://jupyter.org/)

Install with:

```bash
pip install numpy jupyter
```

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/JunaidAshraf05/Numpy.git
   cd Numpy
   ```
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open any notebook (`1.ipynb`, `2.ipynb`, `3.ipynb`) and run the cells step by step.

---

## 📖 Quick Examples

```python
import numpy as np  

# Create a 1D array  
arr = np.array([1, 2, 3, 4, 5])  
print(arr)  # [1 2 3 4 5]  

# Create a 2D array with arange and reshape  
arr2 = np.arange(1, 10).reshape(3, 3)  
print(arr2)  
# [[1 2 3]  
#  [4 5 6]  
#  [7 8 9]]  

# Broadcasting example  
x = np.array([1, 2, 3])  
y = 2  
print(x + y)  # [3 4 5]  

# Matrix multiplication  
A = np.array([[1, 2], [3, 4]])  
B = np.array([[5, 6], [7, 8]])  
print(np.dot(A, B))  
# [[19 22]  
#  [43 50]]  
```

---

## 🎯 Learning Goals

* Build strong fundamentals in NumPy arrays and operations
* Practice essential functions for data analysis and ML workflows
* Develop problem-solving skills with numerical computing in Python

---

## ✨ Author

👤 **Junaid Ashraf**

* GitHub: [@JunaidAshraf05](https://github.com/JunaidAshraf05)

---

👉 This repository is intended for **self-learning** but can also help **beginners** who are starting with NumPy.

---

Do you want me to **generate this README.md file** so you can directly copy-paste/upload into your repo, or just keep it here for reference?
