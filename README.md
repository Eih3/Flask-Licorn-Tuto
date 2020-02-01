:rainbow: Flask Licorn - Tuto Version
===========================

## Git commands [Wiki - Git Commands](https://github.com/Eih3/Flask-Licorn-Tuto/wiki/Git-Commands)

## Creating Virtualenv with Python3
You must have Python 3 and PIP installed on your system.

Go into project root and create venv :
``` shell
$ python3 -m venv .venv 
```

Activate Virtualenv :
``` shell
$ source .venv/bin/activate
```

Deactivate Virtualenv :
``` shell
$ deactivate
```

## Installing Python Requirements
Remember to activate virtualenv directory or all python requirements will be installed
into global environment and not only into your project.

``` shell
$ pip install -r requirements.txt
```

If you need to add/update all python dependencies to requirements.txt
``` shell
$ pip freeze > requirements.txt
```