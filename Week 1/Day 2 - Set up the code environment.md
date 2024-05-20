# Set up the code environment
This guide provides a clear, step-by-step process to help you install Python, set up a virtual environment, and launch JupyterLab.

## Step 1: Install Python
   - Go to [python.org](https://www.python.org/downloads/).
   - Click the "Download Python" button.

2. **Run the Installer:**
   - Open the downloaded installer.
   - Make sure to check the box that says **"Add Python to PATH"**.
   - Click "Install Now" and complete the installation.

## Step 2: Install Virtual Environment
  **Open Command Prompt** 
  - Press `Win + R`, type `cmd`, and hit Enter.

2. **Install `virtualenv`:**
   
   ```
   pip install virtualenv
   ```

## Step 3: Create Virtual Environment
   ```
   python -m venv summerofai
   ```
   This will create a directory named `summerofai` with a new virtual environment.

## Step 4: Activate Virtual Environment
   ```
     summerofai\Scripts\activate
   ```
   After activation, you should see `(summerofai)` at the beginning of your command prompt, indicating that the virtual environment is active.

## Step 5: Install JupyterLab]
   ```
   pip install jupyterlab
   ```

## Step 6: Launch JupyterLab
   ```
   jupyter lab
   ```
   This command will start JupyterLab and open it in your default web browser.

Now, you should have JupyterLab running in your browser, and you can start working on your projects within this environment.
