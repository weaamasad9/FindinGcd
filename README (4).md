
# GCD and Symmetry Check Project

## Project Overview

This Python project provides two functions for working with the **Greatest Common Divisor (GCD)** and checking the symmetry of a list based on GCD calculations.

### 1. `gcd(x, y)`
A recursive function that calculates the **Greatest Common Divisor (GCD)** of two non-negative integers `x` and `y` using the **Euclidean algorithm**.

### 2. `sym_not_coprime(nums)`
A recursive function that takes a list of natural numbers and checks if all pairs of elements at symmetric positions in the list are **not coprime** (i.e., their GCD is greater than 1). The function returns `True` if all symmetric pairs have a GCD greater than 1, otherwise, it returns `False`.

## Function Definitions

### 1. `gcd(x, y)`

#### Parameters:
- `x`: A non-negative integer.
- `y`: A non-negative integer.

#### Returns:
- The GCD of `x` and `y`.

#### Example:

```python
gcd(18, 24)  # Output: 6
gcd(21, 18)  # Output: 3
gcd(5, 4)    # Output: 1
```

### 2. `sym_not_coprime(nums)`

#### Parameters:
- `nums`: A list of natural numbers.

#### Returns:
- `True` if all symmetric pairs of numbers in the list are **not coprime** (i.e., their GCD > 1).
- `False` if at least one symmetric pair is coprime (i.e., their GCD = 1).

#### Example:

```python
sym_not_coprime([2, 4, 6, 3])  # Output: False (2 and 3 are coprime)
sym_not_coprime([6, 12, 18])   # Output: True (no pairs are coprime)
```

## Usage Instructions

To use the provided functions, simply copy the code and execute it in any Python 3 environment. Below is an example usage:

```python
# Example usage of gcd function
print(gcd(18, 24))  # Output: 6

# Example usage of sym_not_coprime function
print(sym_not_coprime([2, 4, 6, 3]))  # Output: False
print(sym_not_coprime([6, 12, 18]))   # Output: True
```

## Installation

Ensure you have Python 3.x installed on your system. No additional libraries are required to run this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

