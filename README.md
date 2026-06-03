# MathLib
[![PyPI version](https://img.shields.io/pypi/v/mathlibtr.svg)](https://pypi.org/project/mathlibtr/)
[![Python Version](https://img.shields.io/pypi/pyversions/mathlibtr.svg)](https://pypi.org/project/mathlibtr/)


A lightweight Python math utility library providing basic arithmetic, number theory, sequence operations, and mathematical helper functions.

📦 Available on PyPI

## Installation

### Install from PyPI

```bash
pip install mathlibtr
```

### Verify Installation

```python
from Core import transactions as ts

print(ts.add(1, 2, 3))
```

### Install from Source

Clone the repository:

```bash
git clone https://github.com/andacberkaye/MathLib.git
cd MathLib
pip install -e .
```

```bash
pip install mathlibtr
```


---

## Features

### Basic Operations
- Addition
- Subtraction
- Multiplication
- Division
- Modulus
- Power
- Absolute value
- Rounding (round, ceil, floor)
- Clamp (value bounding)

### Statistics & Utilities
- Minimum / Maximum
- Average
- Percentage calculations
- Percentage change

### Number Theory
- GCD (Greatest Common Divisor)
- LCM (Least Common Multiple)
- Prime check
- Prime factorization
- Parity (Even / Odd)

### Sequences
- Fibonacci (number / series)
- Range-based sum
- Range-based product

### Geometry
- Distance (2D Euclidean distance)
- Hypotenuse calculation

### Trigonometry (radians)
- sin, cos, tan, cot (Taylor series approximation)
- Degree ↔ Radian conversion

### Mathematical Functions
- Factorial
- Square root
- Cube root
- Nth root

### Advanced Mathematics
- Exponential function (exp)
- Natural logarithm (ln)
- Logarithm (log)
- Sigmoid function
- Numerical derivative (finite difference)
- Numerical integral (trapezoidal rule)

---

## Import

Import the module

```python
    from Core import transactions as ts
```

## Usage Examples

### Basic Operations

```python
    ts.add(1, 2, 3)
    ts.sub(10, 3, 2)
    ts.multi(2, 3, 4)
    ts.division(10, 2)
```

### Advanced Math Functions

```python
    ts.round_number(3.6)
    ts.ceil_number(3.1)
    ts.floor_number(3.9)

    ts.cube_root(27)
    ts.nth_root(16, 4)

    ts.percentage(200, 15)

    ts.sin(0)
    ts.cos(1.5708)
    ts.tan(0.7854)
    ts.cot(0.7854)
    ts.degrees_to_radians(180)
    ts.radians_to_degrees(3.14159)

    ts.hypotenuse(3, 4)

    ts.exp(1)
    ts.ln(2.71828)
    ts.log(8, 2)

    ts.sigmoid(0)

    ts.derivative(lambda x: x**2, 3)
    ts.integral(lambda x: x**2, 0, 1)

    ts.distance_2d(0, 0, 3, 4)
    ts.clamp(150, 0, 100)   
```

### Number Theory

```python
    ts.gcd(60, 36)
    ts.lcm(12, 18)
    ts.prime_factors(84)
    ts.is_prime(13)
```

### Fibonacci

```python
    ts.fibonacci(6, "series")
    ts.fibonacci(6, "number")   
```

### Range Operations

```python
    ts.add_range(1, 5)
    ts.product_range(1, 5)
```

### Square Roots

```python
    ts.sqrt(16)
```

### Basic Operations

```python
    from Core import transactions
```

## Roadmap

-   Expand to 50+ functions
-   Add vector and matrix operations
-   Improve numerical stability (adaptive precision methods)
-   Add unit tests (pytest)
-   Optimize factorial and series computations
-   Add error handling improvements
-   Prepare PyPI release
-   Add documentation site (docs-style)

## Notes

-   Division by zero raises errors
-   Some functions require at least one argument
-   Floating point precision may affect results
-   Trigonometric functions use Taylor series approximation
-   Logarithm and exponential functions use numerical approximations
-   Results may slightly differ from Python's math module

## Status

Under active development (experimental)

## Author

Python math utilities project focused on clean code and modular design.

---