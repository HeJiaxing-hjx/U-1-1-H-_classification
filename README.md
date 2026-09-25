# The Classification of Matrices in $U(1,1;\mathbb H)$ under Similarity and Iteration 

This Jupyter Notebook classifies quaternionic matrices in $U(1,1;\mathbb H)$ under similarity and iteration. Its main features include:

- exact quaternion arithmetic;
- checking whether a $2\times2$ quaternionic matrix belongs to $U(1,1;\mathbb H)$;
- computing matrix powers $T^n$, traces, and related invariants;
- classifying $T^n$ as simple or compound elliptic, parabolic, or loxodromic;
- providing verified examples for the different classification types.

## Requirements

Python 3, Jupyter, and SymPy are required:

```bash
pip install jupyter sympy
```

## Usage

Open `U(1,1;\mathbb H)_classification.ipynb`, run the cells in order, and modify `a`, `b`, `c`, `d`, and the exponent `n` in an input example.

Enter a quaternion as `Quaternion(w, x, y, z)`. To preserve exact arithmetic, use SymPy expressions such as `sp.sqrt(...)`, `sp.pi`, `sp.E`, and `sp.Rational(p, q)` instead of decimal numbers or strings.

- This notebook was written by [Jiaxing He]