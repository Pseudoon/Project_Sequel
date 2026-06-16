# 🚀 ProjectSequel

A lightweight, robust Command Line Interface (CLI) application designed for structured database connectivity, querying, and interactive SQL execution. Built entirely in Python, **ProjectSequel** simplifies managing database sessions, running automated testing scripts, and handling sequential query logic cleanly from the terminal.

---

## 🛠️ Features

* **Modular Database Connectivity:** Dedicated execution layers (`connection_funcs.py`) ensuring clean session opening, closing, and connection pool handling.
* **Streamlined Query Architecture:** Centralized query parsing via `queries.py` and structured external storage in `queries.txt` for easy modification without altering core code.
* **Automated Testing Suite:** Integrated `test.py` script to run immediate end-to-end verification of your query logics and database state.
* **Environment Isolation:** Pre-configured `.gitignore` that completely ignores `venv/`, compiled binary `__pycache__/` files, and local IDE configurations to keep the repository immaculate.

---

## 📂 Project Structure

```text
ProjectSequel-main/
│
├── connection_funcs.py    # Database connection setup, context managers, and error handling
├── main.py                # Core application entry point and interactive CLI loop
├── misc_funcs.py          # Helper utilities, console formatting, and logging modules
├── queries.py             # Internal query parsing logic and execution mapping
├── queries.txt            # External storage file for modular, executionloaded SQL scripts
├── test.py                # Unit and integration testing scripts for verification
├── requirements.txt       # Pinpoints Python dependency packages
└── .gitignore             # Tells Git which files/folders to actively ignore
