# typer-app
application using Python's Typer Library to make a CLI

### Description
This application was created from the demo located on Typer's site here: https://typer.tiangolo.com/
This application was created on OSX 13.2 with Python 3.11 in the z shell (zsh). 

### Requirements
Python 3.6+
```
brew install python
echo "alias python=/usr/local/bin/python3" >> ~/.zshrc
```
install pip
```
python3 get-pip.py
```

### Install instructions for the typer app
git clone this project and change into the directory
```
git clone git@github.com:icefelt/typer-app.git && cd typer-app
```

install typer with pip
```
pip install "typer[all]"
```

### Run the application
To say hello to someone named Scott
```
python main.py hello Scott
```

To say goodbye to someone named Scott
```
python main.py goodbye Scott
```


