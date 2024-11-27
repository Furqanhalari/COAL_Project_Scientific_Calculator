# COAL_Project_Scientific_Calculator
# Overview
The MASM Scientific Calculator is a console-based application developed in Assembly language using the Irvine32 library. It performs a variety of arithmetic, logical, and scientific calculations, including trigonometric functions, logarithmic computations, and binary operations. This project showcases fundamental and advanced features of Assembly programming, including floating-point operations, binary manipulation, and the use of mathematical algorithms.
# Features
The calculator supports the following operations:

## Arithmetic Operations
* Addition
* Subtraction
* Multiplication
* Division
## Logical and Bitwise Operations
* AND
* OR
* XOR
## Scientific Functions
* Sine (sin)
* Cosine (cos)
* Tangent (tan)
## Logarithmic Calculations
* Logarithm (log base 10)
* Natural Logarithm (ln)
## Power and Root Calculations
* Square
* Cube
* Square Root
## Utility
* Input Validation: Ensures correct input formats for binary and numeric data.
* Error Handling: Includes handling for division by zero and invalid inputs.

# How It Works
## Arithmetic Operations
* Accepts two integer inputs and performs the selected operation.
* Results are displayed directly in decimal format.
## Logical and Bitwise Operations
* Accepts two binary inputs (validated) and performs bitwise operations (AND, OR, XOR).
* Outputs are displayed in an 8-bit binary format.
## Scientific Functions
* Trigonometric Functions (sin, cos, tan): Requires input in degrees, converts it to radians, and performs the operation using FPU instructions.
* Logarithmic Functions: Calculates the logarithm (base 10) or natural logarithm using fyl2x and mathematical constants.
## Power and Root Calculations
* Square: Multiplies the number by itself.
* Cube: Multiplies the number by itself twice.
* Square Root: Integer Square root calculation.

# Code Highlights
1) Modular Design: 
Each operation is encapsulated in its own subroutine for clarity and reusability.
2) Input Validation: 
Ensures proper inputs for both binary and numeric data to prevent errors during computation.
Floating-Point Operations: 
Uses the FPU stack for efficient trigonometric and logarithmic calculations.
3) Error Handling: 
Checks for division by zero and invalid menu choices with appropriate error messages.
4) Custom Binary Writer: 
Converts and displays results of logical operations in an 8-bit binary format.

