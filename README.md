# <Project Name>Data Got Talent 2023

## Description

This repository contains the source code and documentation for Data Got Talent 

## Work Environment

### Technologies Used

- Python 3.x
- Jupyter Notebooks
- Librabry: numpy, pandas, xlsxwriter,  ydata-profilling

### Setting Up the Environment
#### Clone the Repository:
    ```bash
    git clone https://github.com/<your-username>/<project-name>.git
    cd <project-name>
    ```
#### Installing Python 3

1. **Download Python:**
   - Visit the official Python website: [Python Downloads](https://www.python.org/downloads/).
   - Click on the "Downloads" tab.
   - Choose the latest version of Python 3.x.
   - Download the installer for your operating system.

2. **Run the Installer:**
   - Execute the downloaded installer.
   - Make sure to check the box that says "Add Python to PATH" during the installation process.
   - Click "Install Now" to start the installation.

3. **Verify Installation:**
   - Open a new terminal or command prompt.
   - Run the following command to check if Python is installed:
     ```bash
     python --version
     ```
     or, for some systems:
     ```bash
     python3 --version
     ```
   - You should see the installed Python version displayed.

## Installing Jupyter Notebook

1. **Install Jupyter using `pip`:**
   - Open a terminal or command prompt.
   - Run the following command:
     ```bash
     pip install notebook
     ```

2. **Verify Jupyter Installation:**
   - After the installation is complete, run the following command:
     ```bash
     jupyter notebook
     ```
   - Access Jupyter Notebook in your web browser at `http://localhost:8888`.

## Installing Library 
After the installation, you can verify that the libraries are installed correctly. Open a Python interpreter or a Jupyter Notebook and run the following commands:
```bash
import numpy
import pandas
import xlsxwriter
import pandas_profiling

print(f"Numpy version: {numpy.__version__}")
print(f"Pandas version: {pandas.__version__}")
print(f"Xlsxwriter version: {xlsxwriter.__version__}")
print(f"Pandas Profiling version: {pandas_profiling.__version__}")
```

**Working with the Code:**
    - All source code is available in the `src` directory.
    - Jupyter Notebooks are in the `notebooks` directory.
    - Run the notebooks using Jupyter for data analysis and exploration.

**Contributing:**
    - If you'd like to contribute to this project, please fork the repository and create a pull request.
## Contact

For any questions or inquiries, please contact:

- **<Your Name>**
  - Email: <your-email@example.com>
  - GitHub: [github.com/<your-username>](https://github.com/<your-username>)

