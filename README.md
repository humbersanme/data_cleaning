# Data Types and Extensions in Pandas

This notebook explores the extensions of data types in pandas, focusing on the library's evolution beyond its reliance on NumPy. It discusses the challenges and improvements in handling missing data, non-numerical data, and computationally expensive operations.

## Contents

### 1. Introduction to Pandas and NumPy
- Explanation of how pandas was originally built on NumPy's array capabilities.
- Overview of pandas' compatibility with NumPy and its limitations.

### 2. Limitations in Handling Data
- Issues with missing data for numerical types like integers and booleans.
- Conversion of data types to `float64` when introducing missing values, leading to subtle issues.
- Challenges with string-heavy datasets, including high memory usage.
- Inefficient support for time-related data types, such as:
  - Time intervals
  - Time deltas
  - Timestamps with time zones

### 3. Extension of Data Types
- Introduction to pandas' new extension type system.
- Benefits of the extension system:
  - Adding support for new data types not natively supported by NumPy.
  - Efficient handling of specialized data types as first-class citizens in pandas workflows.
