# IntrusionDetection_5G

## Introduction

This project focuses on Intrusion Detection in 5G networks using various machine learning models. The system is designed to run on Python 3.9.

## Usage

### Steps to Run Colab Notebooks

1. **Download or Clone the Project**: Obtain the project files from the GitHub main/master branch.
2. **Unpack Data Files**: Unzip the .zip files and folders located in the following paths to access the CSV files used by the models:
   - `IntrusionDetection_5G/data_processed`
   - `IntrusionDetection_5G/data_original`
3. **Create Python Virtual Environment**: Set up a Python virtual environment with Python 3.9 using the following command:
    ```
    python3 -m venv test_env
    ```
4. **Activate the Virtual Environment**:
    - **MacOS**:
        ```
        source test_env/bin/activate
        ```
    - **Windows**:
        ```
        test_env\Scripts\activate
        ```
5. **Install Requirements**: Navigate to the project's home directory (where `requirements.txt` is located) and run the following command:
    ```
    pip install -r requirements.txt
    ```
6. **Run Notebooks**: Execute any .ipynb files to view the results corresponding to the specific model. These files are located in the path `IntrusionDetection_5G/models`.

### Requirements

Ensure the following dependencies are installed:

1. Python 3.9
2. Jupyter Notebook

### Hardware Requirements

1. Windows/Mac Laptop
2. 8GB RAM
3. 128GB SSD Memory
