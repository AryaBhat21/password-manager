# Password Manager

A simple Tkinter-based password manager that generates random passwords and stores website/email/password entries in `data.txt`.

## Features

- Generate a strong random password
- Save website, email/username, and password to a local `data.txt`
- Built with Python `tkinter`

## Files

- `main.py` - Main GUI application and password save logic
- `data.txt` - Data file where saved password entries are appended
- `pyproject.toml` - Poetry project metadata and dependencies
- `poetry.lock` - Locked dependency versions for reproducible installs

## Requirements

- Python 3.8+
- `poetry` (optional, recommended for dependency management)

## Run

### Option A: Using Python directly

1. Open terminal in project folder
2. Run:
   ```bash
   python main.py
   ```

### Option B: Using Poetry

1. Install dependencies:
   ```bash
   poetry install
   ```
2. Run app:
   ```bash
   poetry run python main.py
   ```

## Usage

1. Enter `Website` and `Email/Username`.
2. Click `Generate Password` to fill password.
3. Click `Add` to save entry to `data.txt`.

## Notes

- `logo.png` is required for the UI canvas image; if missing, either add it or remove the `PhotoImage` usage.
- The app stores passwords in plain text in `data.txt`, so this is for learning/demo use only.
