# [Title of the Assistent]

## Table of content
1. [Dev-Hints](#1-dev-hints)<br/>
2. [About this Assistant](#2-about-this-assistant)<br/>
3. [Installing Instructions](#3-installing-instructions)<br/>
4. [Usage](#4-usage)<br/>
<br/>

<div style="text-align: justify;">

## 1. Dev-Hints:
- [Dev. to User: Write here some instructions, how bugs and advices can be communicated.]
- [Dev. to Dev.: Write here some details of your dev-process, or some hints for your coworkers.]


## 2. About this Assistant:
This assistant is an integral component of the research data infrastructure "Historische Quellen" (abbreviated as 'HisQu'). It serves as a collaborative initiative aimed at fostering the systematic organization, analysis, and accessibility of historical sources. For more detailed information about the goals, scope, and participating institutions, please visit the official website at https://hisqu.de/. <br/>
[Write here your Assistent specific discribtion. ]

## 3. Installing Instructions

### Python is necessary
Follow the [Python installation guide](pythonInstalled.md) to make sure you have Python and pip installed on your device.  
This assistant was developed using a specific Python version. If you encounter problems due to version conflicts, please refer to the [Python version guide](pythonVersionDowngrade.md).

### Quickstart on Windows:
1. Download this project as a .zip file to your local device.  
   (Click on "Code," then choose "Download as ZIP.")
2. Open your file manager and extract the .zip file.
3. If available run `quicksetup.bat` by double-clicking it.  
   Note that some operations will be executed in your terminal. Don't be alarmed.

**Step by Step:**  
1. Clone this repository to your local device.  
   - For Windows: Press [Win], type *Terminal*, and press [Enter].  
   - For Mac: Press [Command]+[Space], type "Terminal" in Spotlight, and open the terminal.
2. Navigate the terminal to your save directory. Enter:
   ```
   git clone [URL of the GitHub/ GitLab Repo].git
   ```
   **Alternatively:** If you don't have Git installed, download the project as a .zip file and extract all data into a folder.

3. Change to the root directory:
   ```
   cd [folder name (probably the same like your rempo name)]
   ```

4. [Create and activate a virtual environment](pythonVenv.md) in your project folder.

5. [Install all required Python packages](pythonRequiermentsText.md) using the `requirements.txt` file. This will also install all submodules recursively.

6. [Set up your `.env` file](openAIEnv.md) with the necessary variables for OpenAI access.

## 4. Usage
Open your terminal (for detailed instructions, see section 3.1).  
To run the assistant, type the following command and press Enter:
```
python scripts/NER_pipeline.py
```

</div>
