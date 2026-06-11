 Ai-Upskilling

Python Installation
Verify Python Installation
python --version
Expected Output:
Python 3.14.5
Verify Python Launcher
py --version
Expected Output:
Python 3.14.5


Verify pip Installation
pip is Python's package manager.
Check pip version:
pip --version
Expected Output:
pip xx.x from C:\Program Files\Python

Python Interpreter

Python code cannot run directly on the computer.

The Python Interpreter reads Python code and executes it.

Example:

print("Hello")

Execution Flow:

Python Code
     ↓
Python Interpreter
     ↓
Machine Instructions
     ↓
Output

Interpreter Location:
C:\Program Files\Python\python.exe


Virtual Environment (.venv)
A virtual environment isolates project dependencies.

Create:

python -m venv .venv

Activate:

.\.venv\Scripts\Activate.ps1

Prompt changes to:

(.venv) PS>

Deactivate:
deactivate
