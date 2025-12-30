# Function-Grapher

[![CI](https://github.com/ZayThihaAung/Function-Grapher/actions/workflows/python-package.yml/badge.svg)](https://github.com/ZayThihaAung/Function-Grapher/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)

This program is designed to graph absolute, square root, linear and quadratic functions using Python. It's intended to be helpful for students learning function shapes and parameters.

Features
- Plot absolute value, square-root, linear and quadratic functions
- Customizable plotting ranges and parameters
- Uses matplotlib and numpy for crisp visuals
- Example usage and command-line instructions included

Quick start

1. Clone the repository:
   ```
   git clone https://github.com/ZayThihaAung/Function-Grapher.git
   cd Function-Grapher
   ```

2. Create a virtual environment and install dependencies:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Run the grapher script
   Replace `function_grapher.py` below with the entry script in this repository (if it has a different name).
   ```
   python function_grapher.py
   ```
   Or run a quick example from Python:
   ```python
   from example import plot_quadratic  # replace with actual module/script names
   plot_quadratic(a=1, b=0, c=0, x_range=(-10, 10))
   ```

Usage examples
- Plot a quadratic: set coefficients a, b, c
- Plot a linear function: set slope m and intercept b
- Plot absolute value and square-root functions with domain/range options

If your repo uses a specific script name, replace the examples above with that script name. If you'd like, I can examine the repository and add exact run commands.

Repository layout (suggested)
- function_grapher.py (main script / UI)
- src/ or lib/ (optional: library modules)
- examples/ (example scripts)
- tests/ (unit tests)
- docs/ (usage & screenshots)

Contributing
- Please read CONTRIBUTING.md for guidelines.
- Open issues for features or bugs.
- Pull requests welcome!

License
- This project is licensed under the MIT License — see the LICENSE file for details.

Contact
- Maintainer: ZayThihaAung
- Repo: https://github.com/ZayThihaAung/Function-Grapher
