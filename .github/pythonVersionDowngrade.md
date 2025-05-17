# Changing your Python Version

<div style="text-align: justify" >

## Table of Contents
1. [Why might I need an older Python version?](#1-why-might-i-need-an-older-python-version)
2. [How to check your current Python version](#2-how-to-check-your-current-python-version)
3. [How to install an older Python version (Windows, macOS, Linux)](#3-how-to-install-an-older-python-version-windows-macos-linux)
4. [How to use a specific Python version](#4-how-to-use-a-specific-python-version)

## 1. Why might I need an older Python version?

Some projects or assistants may only work with certain versions of Python. If you have a newer version installed, but the assistant does not work as expected, you may need to install an older version (for example, Python 3.10 or 3.11).

## 2. How to check your current Python version

- **Windows:**  
  Open the Command Prompt and type:
  ```
  python --version
  ```
- **macOS/Linux:**  
  Open the Terminal and type:
  ```
  python3 --version
  ```

## 3. How to install an older Python version (Windows, macOS, Linux)

- **Windows:**  
  (1) Go to the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
  (2) Scroll down to "Looking for a specific release?" and click on the version you need (for example, Python 3.10.13).
  (3) Download the installer for your system (usually "Windows installer (64-bit)").
  (4) Run the installer.  
     - **Important:** Check the box **"Add Python to PATH"** before clicking "Install Now".
  (5) Follow the instructions to finish the installation.

- **macOS:**  
  You can use a tool called [Homebrew](https://brew.sh/).  
  Open Terminal and type:
  ```
  brew install python@3.10
  ```
  After installation, you may need to use `python3.10` to run Python.

- **Linux:**  
  You can often install older versions using your package manager, or by downloading from [python.org](https://www.python.org/downloads/).  
  For Ubuntu/Debian, you can use:
  ```
  sudo apt-get update
  sudo apt-get install python3.10
  ```

## 4. How to use a specific Python version

If you have more than one Python version installed, you may need to specify which one to use:

- **Windows:**  
  In Command Prompt, type:
  ```
  py -3.10
  ```
  or use the full path to the Python executable.

- **macOS/Linux:**  
  In Terminal, type:
  ```
  python3.10
  ```

**Hint:** If you are unsure which version to use, ask your project contact or refer to the project documentation.

</div>