# Installing Required Python Packages

## What is the `requirements.txt` file?

The `requirements.txt` file lists all the Python packages that your project needs to work correctly. These packages are like tools or building blocks that the assistant uses. By using this file, you can easily install everything needed with just one command, instead of installing each package one by one.

## How to install all required packages (including submodules)

To make sure your project works, you need to install all packages listed in the `requirements.txt` file. This process will also install any packages needed by submodules (parts of the project that are included from other sources). This is called "recursive installation" and ensures that everything is set up correctly.

1. Open your terminal (Command Prompt on Windows, Terminal on macOS/Linux).
2. Navigate to the folder where your `requirements.txt` file is located.
3. Run the following command:

   ```
   pip install -r requirements.txt
   ```

This command will automatically find and install all the necessary packages, including those required by any submodules. The process may take a few minutes. Once it is finished, your project will be ready to use.