# Creating and Using a Python Virtual Environment

## What is a virtual environment (VENV)?

A virtual environment is a special folder on your computer where Python stores all the packages and settings just for your project. This keeps your project’s packages separate from other projects and from the main Python installation on your computer. Using a virtual environment helps avoid conflicts and makes your project easier to manage.

## How to create a virtual environment

1. Open your terminal (Command Prompt on Windows, Terminal on macOS/Linux).
2. Go to the folder where your project is located.
3. Type the following command and press Enter:

   ```
   python -m venv .venv
   ```

   This will create a new folder called `.venv` in your project directory.

## How to activate the virtual environment

- **Windows:**
  ```
  .venv\Scripts\activate
  ```
- **macOS/Linux:**
  ```
  source .venv/bin/activate
  ```

After activation, you will see the name of the virtual environment (usually `.venv`) at the beginning of the command line. Now, any Python packages you install will only affect this project.

**Tip:** Remember to activate the virtual environment every time you start working on your project.