# NumPy Analyzer

---

## Project Overview

NumPy Analyzer is a menu-driven Python application developed using Object-Oriented Programming (OOP) principles and the NumPy library.

The application enables users to create, manipulate, and analyze NumPy arrays interactively. The entire control flow of the program is implemented using Python’s `match-case` statement, and the core functionality is encapsulated within a class named `Da`.

---

## Folder Structure

```
Numpy-Analyzer/
│
├── main.py
└── README.md
```

---

## Features and Functionalities

### 1. Class and Object Structure
- Class Name: `Da`
- Constructor-based initialization
- Encapsulation through private helper methods
- Implementation of:
  - Instance methods
  - `@classmethod`
  - `@staticmethod`

---

### 2. Array Management

#### Array Creation
- 1D Arrays
- 2D Arrays
- 3D Arrays

#### Indexing and Slicing
- Access specific elements
- Extract rows and columns
- Perform subarray slicing

#### Combining and Splitting
- Vertical stacking (concatenation)
- Splitting arrays into smaller arrays

---

### 3. Mathematical Operations
- Element-wise Addition
- Element-wise Subtraction
- Element-wise Multiplication
- Element-wise Division
- Dot Product
- Matrix Multiplication (for 2D arrays)

---

### 4. Search, Sort, and Filter
- Search for specific values
- Sort arrays in ascending order
- Sort arrays in descending order
- Filter arrays based on user-defined conditions

---

### 5. Aggregates and Statistical Functions
- Sum
- Mean
- Median
- Standard Deviation
- Variance
- Minimum
- Maximum
- Percentile
- Correlation coefficient between arrays

---

## Sample Program Output

```
Welcome to the NumPy Analyzer!

Choose an option:
1. Create a Numpy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit

Enter your choice: 1

Array Creation:
Select the type of array to create:
1. 1D Array
2. 2D Array
3. 3D Array
Enter your choice: 2
Enter the number of rows: 2
Enter the number of columns: 3
Enter 6 elements for the array separated by space: 10 20 30 40 50 60
Array created successfully:
[[10 20 30]
 [40 50 60]]

Choose an operation:
1. Indexing
2. Slicing
3. Go Back
Enter your choice: 2
Enter the row range (start:end): 0:2
Enter the column range (start:end): 1:3
Sliced Array:
[[20 30]
 [50 60]]

Choose an option:
1. Create a Numpy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit

Enter your choice: 6
Thank you for using the NumPy Analyzer!
Goodbye!
```

---

## Author

Patel Tej

