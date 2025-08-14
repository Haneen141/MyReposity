# MyReposity

**Project Type:** Simple Python Demo  
**Goal:** Upload a simple Python project to GitHub and document all the steps I followed.

## Files
- `main.py` — A simple Python script that prints a message.
- `.gitignore` — To ignore the `env` folder and temporary files.
- `README.md` — This file explains the project and steps.

## Steps I followed
1. Created a new folder for the project on my computer.
2. Initialized Git in the folder:
   ```bash
   git init
   ```
3. Created a Python virtual environment:
   ```bash
   python -m venv env
   ```
4. Activated the virtual environment:
   ```bash
   source env/Scripts/activate   # For Git Bash
   ```
5. Created `main.py` and added a simple Python script.
6. Created `README.md` and wrote the project description.
7. Created `.gitignore` and added `env/` to ignore the virtual environment.
8. Added all files to Git staging:
   ```bash
   git add .
   ```
9. Committed the files:
   ```bash
   git commit -m "Initial commit: add main.py, README.md and .gitignore"
   ```
10. Added the GitHub remote repository:
    ```bash
    git remote add origin git@github.com:Haneen141/MyReposity.git
    ```
    ```
11. Pushed the files to GitHub:
    ```bash
   git push -u origin main
## How to run the project locally
1. Clone the repository:
   ```bash
   git clone git@github.com:Haneen141/MyReposity.git
   cd MyReposity
   ```
2. Activate the virtual environment:
   ```bash
   source env/Scripts/activate   # Git Bash
   ```
3. Run the Python script:
   ```bash
   python main.py
   ```
