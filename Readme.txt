Steps to install:

1. Create a virtual env: pythim -m venv ai
2. Activate the virtual environment: .\ai\Scripts\Activate.ps1

# In case it is showing permission error: Open PowerShell as admin and type this command:   
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

3. Install the requirements: pip install -r requirements.txt
4. Run using streamlit: streamlit run main.py