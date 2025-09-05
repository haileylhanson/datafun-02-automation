# datafun-02-automation
CC2.1: Start a Python Automation Project


# datafun-02-project-setup
Utilities for scripting project folders

*****************************************************
Features 5 functions which
    1- create local folders from a range of integers
    2- create local folders given a list of string names
    3- create local folders given a list of string names and appending a specific prefix onto the beginning of every folder
    4- create local folders every X seconds (with a 60 second time limit)
    5- convert a list of folder names by removing spaces & making all-lowercase  
*****************************************************

## Project Requirements

- VS Code
- Git
- Python 

## Professional Python Workflow

See [pro-analytics-01](https://github.com/denisecase/pro-analytics-01/)

## Commands to Manage Virtual Environment

For Windows PowerShell (change if using Mac/Linux).
Verify that all required packages are included in requirements.txt (and have NOT been commented out).


```powershell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
```

## Commands to Run Python Scripts

Remember to activate your .venv (and install packages if they haven't been installed yet) before running files.


```shell
python3 utils_haileyhanson.py
python3 haileyhanson_project_setup.py
```

## Commands to Git add-commit-push

```shell
git add .
git commit -m "custom message"
git push -u origin main
```

## Reference Projects

Custom implementation of the example project at 
[datafun-02-project-setup](https://github.com/denisecase/datafun-02-project-setup)

- [Module 1 Repo](https://github.com/denisecase/datafun-01-utils/)