# Meet++
A application that improves your Google Meet hosting experience by sending you message notifications if someone types in chat.

_This application is tested on pc with:_

OS: Windows 11

Python Version: 3.11

Browser: Microsoft Edge

If you want to use chrome, opem meet++GUI.py file and uncomment those lines with the comment '_chrome_' and comment those lines with comment '_edge_'

## Dependencies:
 - Selenium
 - win10toast
 - Python 3.x

### How to run: 
 1. Clone this repo.
 2. Open terminal inside this folder
 3. Make a virtual environment (Optional) for package isolation:
    ```
        python -m venv <env_name>
    ```
 4. Activate the virtual environment (if you did 3rd step):
    
    ### For Windows:
    ```
        "env/scripts/activate"
     ```
    ### For Linux:

    ```
        "source env/bin/activate" for linux
    ```
 5. Download the dependencies using the command
    ```
        pip install -r requirements.txt
    ```
 6. Run meet++GUI.py by:
    ```
        python meet++GUI.py
    ```