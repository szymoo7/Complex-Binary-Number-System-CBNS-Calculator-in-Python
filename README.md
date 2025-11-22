# Complex Binary Number System (CBNS) Calculator in Python

This project implements a simple calculator for complex numbers using the Complex Binary Number System (CBNS). It allows conversion between standard complex numbers and their CBNS representation, as well as basic arithmetic operations.  
This task was prepared as part of the course "Computer Organization and Architecture".


---

## Features

* Convert complex numbers to CBNS representation
* Convert CBNS strings back to complex numbers
* Perform arithmetic operations in CBNS:

  * Addition
  * Subtraction
  * Multiplication
  * Division (with division-by-zero handling)
* Input numbers in binary form for real and imaginary parts

---

## How It Works

1. **Complex to CBNS Conversion**
   The `complex_to_cbns(z: complex)` function converts a complex number `z` into its CBNS string using base `-1 + i`.

2. **CBNS to Complex Conversion**
   The `cbns_to_complex(s: str)` function converts a CBNS string back to a standard Python `complex` number.

3. **Arithmetic Operations**
   Functions `add_cbns(a, b)`, `sub_cbns(a, b)`, `mul_cbns(a, b)`, and `div_cbns(a, b)` perform the corresponding operations by converting CBNS strings to complex numbers, performing the operation, and returning both the result as CBNS and as a complex number.

4. **Example Input**
   The script accepts user input in **binary strings** for the real and imaginary parts of two complex numbers.

---

## Example Usage

```text
Real part of the 1st number (binary): 101
Imaginary part of the 1st number (binary): 10
Real part of the 2nd number (binary): 11
Imaginary part of the 2nd number (binary): 1
```

The script will then compute CBNS representations and the results of addition, subtraction, multiplication, and division.

---

## Technologies Used

* Python 3
* Built-in `complex` type
* Standard library only (no external dependencies)

---

## Project Structure

```
├── main.py        # Main script implementing CBNS conversion and arithmetic
└── README.md      # Project documentation
```

---

## Purpose

## Purpose

The purpose of this project is to explore the Complex Binary Number System (CBNS) and practice working with complex numbers in Python. This project was completed as part of the course "Computer Organization and Architecture".
