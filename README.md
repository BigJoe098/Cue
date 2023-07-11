# Cue
A desktop application developed using PyQt5, It is a scheduler and notes tracking software. Done as a project to learn PyQt5 framework in python

# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone https://github.com/BigJoe098/Cue
    $ cd {{ Path to directory with the project }}
    
Follow along as your requirments as below.

### Virtualenv

If you want to install the virtualenv then you will need to first create the virtual enviroment then follow along with the steps in no
virtual enviroment

FOR LINUX/MAC:
  
    $ sudo apt-get install python3.6-venv
    $ python3 -m venv env
    $ source env/bin/activate
  
  
FOR WINDOWS:
  
    $ py -m pip install --user virtualenv
    $ py -m venv env
    $ .\env\Scripts\activate

Do the same steps as in no virtualenv.

### No virtualenv

This assumes that `python3` is linked to valid installation of python 3 and that `pip` is installed and `pip3`is valid
for installing python 3 packages.

Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

If you don't have requiremnts installed for python 3 then run:

    $ pip install -r requirements.txt
    
And then (The home.py is in the code folder as such it is necessary to cd into code folder):

    $ python home.py
      

### Existing virtualenv

If your project is already in an existing python3 virtualenv first install requirements by running

    $ pip install -r requirements.txt
    
And then (The home.py is in the code folder as such it is necessary to cd into code folder):

    $ python home.py
