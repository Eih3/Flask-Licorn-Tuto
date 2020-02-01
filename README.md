:rainbow: Flask Licorn - Tuto Version
===========================

## Learn Git commands
You must have Git installed on your system

###Git Config [Username, Email]
Check if Git username is registered :
``` shell
$ git config --global user.name 
```
Else set your Git username :
``` shell
$ git config --global user.name "your username"
```
Check if Git email is registered :
``` shell
$ git config --global user.email 
```
Else set your Git email :
``` shell
$ git config --global user.email "your@email.com"
```

###Git Clone 
Clone remote github project into a local directory

``` shell
$ git clone https://github.com/Eih3/Flask-Licorn-Tuto.git
```

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
into global environment and not only into your project

``` shell
$ pip install -r requirements.txt
```

If you need to add/update all python dependencies to requirements.txt
``` shell
$ pip freeze > requirements.txt
```