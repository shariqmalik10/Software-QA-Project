# Software QA Project 

## Introduction 
This is a project built as part of the FIT2107 course at Monash. The project involves making a custom calculator web app for a problem set that was given using Flask and then running test using Python's unittest framework

## Types of test carried out 
1. Unit tests
2. Integration Tests

The tests carried out ensured that every functionality was covered and that the components worked well individually as well as when the whole app was compiled

## Setting up and running the project via the terminal

### Enabling virtualenv
To use virtualenv, you will need to have pip, the Python package installer, already installed on your machine (by default, it should also be installed when you install Python).

1. Windows
    ```
    python3 -m venv env
    .\env\Scripts\activate
    ```

2. Linux/macOS
    ```
    python3 -m venv env
    source env/bin/activate
    ```

    If you are unable to get virtualenv to run, you might need to run the following command first:
    ```
    sudo apt install python3-venv
    ```

### Installing Required Dependencies/Packages
You will need to install project dependencies for the provided code to work. This only needs to be done once.

```
pip install -r requirements.txt
```

### Exiting Virtualenv
Once you are finished working on the project, you can exit virtualenv by running the following command:

```
deactivate
```
