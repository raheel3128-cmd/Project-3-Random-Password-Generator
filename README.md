
# Random Password Generator

## Project 3 — Python Programming

A simple Python command-line tool that generates a random, complex password using **letters and numbers**.

This project is based on the DecodeLabs Industrial Training Kit Project 3 requirements.

## Features

- Asks the user for the desired password length.
- Generates a random password.
- Uses uppercase and lowercase letters.
- Uses numbers from 0–9.
- Validates that the entered length is at least 4.
- Handles invalid/non-numeric input without crashing.
- Uses Python's built-in `random` and `string` modules.

## Technologies

- Python 3
- `random`
- `string`

No external packages are required.

## How to Run

1. Make sure Python 3 is installed.
2. Open a terminal in this project folder.
3. Run:

```bash
python password_generator.py
```

If your system uses `python3`, run:

```bash
python3 password_generator.py
```

## Example

```text
=============================================
       RANDOM PASSWORD GENERATOR
=============================================
Enter password length (minimum 4): 8

Generated Password:
a7K2mP9x
Password length: 8 characters
```

The generated password will be different each time because it is randomly created.

## Project Requirement

The project asks the user for a password length (for example, 8 characters) and generates a random password using letters and numbers. This implementation fulfills that core requirement.

The PDF also suggests optional improvements such as allowing special characters and ensuring at least one number. Those enhancements are not required for the basic version, but they can be added later.

## Files

- `password_generator.py` — main Python program
- `README.md` — project documentation

## Author
Raheel Rizwan
Python Programming Project 3
DecodeLabs Industrial Training Kit
Batch 2026
