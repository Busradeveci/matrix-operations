# Matrix Operations with NumPy

This project demonstrates basic matrix operations using Python and the NumPy library. The operations include:

- Creating a random 3x3 matrix
- Transposing the matrix
- Calculating the determinant
- Calculating the inverse of the matrix (if possible)

## 🧮 Example Output

```python
Original Matrix:
 [[5 1 7]
  [9 2 3]
  [4 6 8]]

Transpose Matrix:
 [[5 9 4]
  [1 2 6]
  [7 3 8]]

Determinant: 76.99999999999999

Inverse Matrix:
 [[ 0.09090909 -0.45454545  0.27272727]
  [ 1.13636364 -0.40909091 -0.68181818]
  [-0.59090909  0.59090909  0.04545455]]
```

## 🔧 Requirements

- Python 3.x
- NumPy

You can install NumPy using pip:

```bash
pip install numpy
```

## 🚀 How to Run

```bash
python matrix_operations.py
```

## 📁 File Structure

```
matrix-operations/
├── matrix_operations.py
└── README.md
```

## 📌 Notes

- If the determinant of the matrix is zero, the inverse does not exist and an appropriate message will be displayed.
- This is a simple educational script for learning linear algebra with Python and NumPy.

## 📚 Topics Covered

- Matrix creation
- Transpose
- Determinant
- Inverse
```