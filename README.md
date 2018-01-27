# VSCODE Manual

## Table of Contents

* [Install](#install)
* [Auto Format](#auto-format)

## Install

```bash
# require curl
sudo apt install curl

# curl package
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg

# move file
sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg

# create repo
sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'

# update apt
sudo apt-get update

# install vscode
sudo apt-get install code
```

## Auto Format

```
# install extension
Prettier - Code format

# setting preferences
"editor.formatOnSave": true
```
