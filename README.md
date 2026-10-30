# Hash-Cracker-GUI

HashCracker GUI is a lightweight, user-friendly application designed to efficiently crack password hashes using dictionary-based attacks. Built with Python and powered by CustomTkinter, the tool provides a modern graphical interface that simplifies hash-cracking tasks for ethical hacking, penetration testing, and educational purposes.

## Features

- Supports multiple hash algorithms (e.g., MD5, SHA1, SHA256, etc.).
- Drag-and-drop functionality for hash and wordlist files.
- Real-time process count and output updates.
- Configurable number of words per process for optimized performance.
- Cross-platform GUI with a modern design using CustomTkinter.

## Installation

To run HashCracker locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ayushbrmn08/Hash-Cracker-GUI.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Hash-Cracker-GUI
   ```
3. Set up a Python virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate      # Mac/Linux
   venv\Scripts\activate         # Windows (cmd/PowerShell)
   source venv/Scripts/activate  # Windows (Git Bash)
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the application:
   ```bash
   python Hash_Cracker_GUI.py
   ```

> **Note:** On some systems, `python3` is not recognized as a command — use `python` instead. If `pip install` fails on `tkinterdnd2`, make sure you're on a recent version of Python 3 (3.9+) and that pip itself is up to date (`python -m pip install --upgrade pip`).

## Usage

To use HashCracker:

1. Open the application by running the Python script.
2. Select the hash algorithm from the dropdown menu.
3. Enter or drag-and-drop the target hash you want to crack.
4. Choose a wordlist file containing potential password candidates.
5. Set the number of words per process.
6. Click "Start Cracking" to begin the process.
7. View the real-time output in the console for cracked passwords.

## ScreenShot

<img width="1920" height="1080" alt="390563766-bf2fcedd-be3b-41ac-af36-14c30abe8d72" src="https://github.com/user-attachments/assets/8b8317dd-05b7-42d1-827c-db1e02d5747a" />


## Troubleshooting

**Q: The application is not starting.**

- Ensure that all dependencies are installed by running `pip install -r requirements.txt`.
- Make sure you're running `Hash_Cracker_GUI.py` (not `hashcracker.py`).

**Q: `pip install -r requirements.txt` fails.**

- Confirm you're using Python 3.9 or newer: `python --version`.
- Upgrade pip first: `python -m pip install --upgrade pip`.
- If `tkinterdnd2` specifically fails to install, try installing it on its own (`pip install tkinterdnd2`) to isolate the issue.

**Q: How do I add more words to the wordlist?**

- Simply provide a larger wordlist file or modify the current one with additional password candidates.
