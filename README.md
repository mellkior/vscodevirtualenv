# Python Virtual Environments in Visual Studio Code
_________________________________________

## open a terminal:
#### ```  ctrl+` ```
- Make sure it is a command prompt (cmd) and not powershell or something else

## update pip:
#### `python -m pip install --upgrade pip`

## install virtualenv:
#### `python -m pip install virtualenv`

## create a virtual environment called "env": 
#### `python -m virtualenv env`
- The environment can have any name, "env" is my preference

## activate the virtual environment:
#### `env\Scripts\activate`
- VS Code should automatically activate your virtual environment when you open new terminals as long as you select "env" as your python interpreter. Use `ctrl+shift+p` to view the command palette and search for "python: select interpreter" if it is not automatically selected.

## Within your virtual environment, see what packages are installed:
#### `pip freeze`

## Install required packages
#### `pip install <package_name>`

## Write all dependencies (installed packages) to a file:
#### `pip freeze > requirements.txt`
- you **don't** need to create the txt file beforehand

## Install all dependencies (packages) in requirements.txt: 
#### `pip install -r requirements.txt`

