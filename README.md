# Python Testing Demo

A small calculator project for learning pytest and GitHub Actions.

## Install dependencies

```bash
python -m pip install -r requirements.txt
```

## Run tests

```bash
python -m pytest -v
```

## What is tested?

- Addition
- Subtraction
- Multiplication
- Division
- Remainder
- Division by zero

GitHub Actions automatically runs the tests on pushes to main
and pull requests targeting main.