<img align="right" width="100" src="https://lh3.googleusercontent.com/proxy/21-A-tn6Jb66tns9zQ8ST6RDjgTVitrm6RzhljE4YZB9Dya3C6LDyZX7kWJgXyv9W7GtMpIKgc6fmhaas-cIf5bVlO9pf3I8VwkTnbo3GyaK2s9zRqBhpTDsQz_918MVyIdOvl6hwHh6biun9cLhJcUY5yqHn8XaSuIJKAVKuIVmJQhKT-jVHCwwKcDIz-jaMqLdKDR7eSxBINDgjQ">

Flask Licorn - Tuto Version
===========================
✨ Ready to become a genius with **Flask** ? ✨

## About
<img align="right" width="150" src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg">

I'm Michel, Full-Stack Dev. I would like to share with you some of **Flask** stuffs.

With this tutorial, u'll be able to start with **Flask** Development.

## Let's start !
**Feel free to check the [Wiki Page](https://github.com/Eih3/Flask-Licorn-Tuto/wiki) of this tutorial.**

## Table of Contents
- [About](#about)
- [Learn Git](#learn-git-version-control-tools)
- [Creating Virtual Environment](#creating-virtual-environment)
- [Install Requirements.txt](#install-python-requirements)
- [License](#license)

## Learn Git (Version Control Tools) 
You must have Git installed on your system.
<details>
<summary>Show Git Commands</summary>

### Git Config [Username, Email]
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

### Git Clone 
Clone remote github project into a local directory.
``` shell
$ git clone https://github.com/Eih3/Flask-Licorn-Tuto.git
```

### Git Status
To check the status of files you’ve changed in your working directory, 
i.e, what all has changed since your last commit.

Type this command in your working directory. lists out all the files that have been changed.
``` shell
$ git status
```

### Git Add
Adds changes to stage/index on your working directory.
``` shell
$ git add .
```
or make it more explicit.
``` shell
$ git add -p
```

### Git Commit
Commits your changes and sets it to new commit object for the remote project.
``` shell
$ git commit -m "commit message"
```

### Git Push / Pull
Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. 
Or if your remote has updated and you want those latest changes.
``` shell
$ git push
```

### Git Branch
Lists out all the branches of the project.
``` shell
$ git branch
```

### Caching your Github Password in Git terminal
Bored to always retype Username + Password to Push into remote Github Project ?
Type this command to cache credentials.

on Linux :
``` shell
$ git config --global credential.helper cache

$ git config --global credential.helper 'cache --timeout=3600'
# Set the cache to timeout after 1 hour (timeout in seconds)
```

on Mac :
``` shell
$ git config --global credential.helper osxkeychain
# Set git to use the osxkeychain credential helper
```

on Windows :
``` shell
$ git config --global credential.helper wincred
```
</details>


## Creating Virtual Environment
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


## Install Python Requirements
Remember to activate virtualenv directory or all python requirements will be installed
into global environment and not only into your project.

``` shell
$ pip install -r requirements.txt
```

If you need to add/update all python dependencies to requirements.txt
``` shell
$ pip freeze > requirements.txt
```

## License

[MIT][mit] © [Eih3][author]

[mit]:      http://opensource.org/licenses/MIT
[author]:   http://github.com/eih3