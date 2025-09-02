# Derivative_Program
# 🧮 Limit and Derivative Calculator (Python CLI)

This is a beginner-friendly Python project created after completing an **Introduction to Programming** course.  
It applies core Python concepts like dictionaries, loops, functions, and classes to solve real mathematical problems such as **limits** and **derivatives**.

## ✨ Features

- 📐 Calculate **limits of polynomials** at a specific point
- ➗ Evaluate **limits of rational functions**, with automatic L’Hôpital’s Rule if needed
- 🧠 Handle **symbolic expressions** using SymPy (e.g., `sin(x)/x`, `ln(x)/x`)
- 📉 Compute **derivatives of polynomials**
- 📄 Save results automatically to `Limit.txt`
- 💬 Simple, interactive command-line interface (CLI)

## 🛠 Technologies Used

- Python 3
- [SymPy](https://www.sympy.org/en/index.html) – for symbolic math
- Custom logic for evaluating limits and derivatives

## 📥 Installation

```bash
git clone https://github.com/your-username/limit-derivative-calculator.git
cd limit-derivative-calculator
pip install sympy
python limit_calculator.py
## Example Usage
### Polynomial Limit
```bash
Choose 'Poly'
Enter degree: 2
Enter coefficients: 1 -3 2   # for x² - 3x + 2
x approaches: 2
Result: 0
### Rational Limit with L’Hôpital
```bash
Choose 'Rati'
Numerator degree: 1 → Coefficients: 1 -1
Denominator degree: 1 → Coefficients: 1 -1
x approaches: 1
Result: 1.0
### Symbolic Limit
```bash
Choose 'Function'
Numerator: sin(x)
Denominator: x
x approaches: 0
Result: 1
## File Structure

├── limit_calculator.py     # Main script
├── Limit.txt               # Output log
├── README.md               # Project description
## Future Improvements
 Add derivative calculation directly to CLI

 Add support for more math operations (integrals, graphs)

 GUI version (Tkinter or web-based)

 Improve input validation and error handling

## About This Project
This project was built as a practical application after completing an Introduction to Programming course.
It combines basic programming skills with foundational calculus concepts, demonstrating how even beginner-level code can solve meaningful problems.

### License
MIT License © 2025 [Pham Hong Hieu]
