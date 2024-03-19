# Getting Started

This repository provides a Streamlit application that leverages a RESNET152V2 model trained on the [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).

## Guide
1. [Prerequisites](#prerequisites)
2. [Setting Up a pyenv Environment in VS Code](#setting-up-a-pyenv-environment-in-vs-code)
3. [Downloading the Trained Model](#downloading-the-trained-model)
4. [Running the Streamlit Application](#running-the-streamlit-application)
5. [Additional Notes](#additional-notes)

## Prerequisites

Before you begin, ensure you have the following installed:

1. **Python 3.x**: Verify by running `python --version` or `python3 --version` in your terminal. Download Python from [here](https://www.python.org/downloads/) if needed.
2. **pyenv**: Follow the instructions [here](https://github.com/pyenv/pyenv) if you don't have it.
3. **VS Code**: Download and install VS Code from [here](https://code.visualstudio.com/).
4. **Streamlit**: Install using pip: `pip install streamlit`.

## Setting Up a pyenv Environment in VS Code

1. **Create a virtual environment:**

    Navigate to your project directory in the terminal and run:
    ```bash
    # CD to the project dir
    pyenv local {version}  # for specific Python version
    python -m venv venv
    ```

2. **Activate the virtual environment:**
    ```bash
    .\venv\Scripts\Activate
    python --version
    ```

3. **Install project dependencies:**

    Once the virtual environment is activated, install required dependencies using:
    ```bash
    pip install -r requirements.txt
    ```
    If there's no `requirements.txt`, create one listing all necessary libraries.

## Downloading the Trained Model

1. **Visit the download link:**

    Go to the provided download link for the trained model: [Download Link](https://mega.nz/file/ou9wxaIC#9h1aE--5DL0OZbKIkQ3dvYy6MF4Lf7Td9YDHpWsfxfA).

2. **Download the model:**

    Follow instructions on the MEGA website to download the model file.

3. **Place the downloaded model file:**

    Put the downloaded model file in the appropriate location within your project directory.

## Running the Streamlit Application

1. **Open VS Code:**

    Open VS Code and navigate to your project directory.

2. **Run the Streamlit app:**

    In your terminal (within the activated virtual environment), run:
    ```bash
    streamlit run main.py
    ```
    This will launch your Streamlit application in a web browser window.

## Additional Notes

- Ensure the downloaded model file is placed correctly within your project directory, as referenced by your Streamlit application code.
- The command `streamlit run main.py` assumes your Streamlit app's filename is `main.py`. If it's different, replace it accordingly.

