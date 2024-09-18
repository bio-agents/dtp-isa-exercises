# Exercises for creating ISA-based experimental descriptions

This repository contains the following notebooks:
1. [“Jupyter Notebook - Introduction”](https://github.com/ISA-agents/dtp-isa-exercises/blob/master/1_Jupyter_Notebook_Introduction.ipynb): this introduction will show how Jupyter notebooks work (open this notebook first)
1. [“ISA Jupyter Notebook - Exercise”](https://github.com/ISA-agents/dtp-isa-exercises/blob/master/2_Jupyter_Notebook_ISA_Exercise.ipynb): this exercise demonstrates how to build [ISA](http://isa-agents.org)-based experimental descriptions programmatically, using the concepts from the study design.


## Run in binder

You can run the notebooks in this repository using the [Binder](https://mybinder.org/) agent by clicking on the button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ISA-agents/dtp-isa-exercises/master)

For more information on how the Binder agent works, check [its documentation](https://mybinder.readthedocs.io).

## Run in your local machine

You can also choose to run the notebooks in your local machine, as detailed below. You will need *Python 3.6*, *jupyter*, and *virtualenv* (if you want to use virtual environments).

If you do not want to use a [virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/), skip the first two steps below:

1. Clone this repository: ```git clone https://github.com/ISA-agents/dtp-isa-exercises.git```  
1. Get into the repository: ```cd dtp-isa-exercises```
1. Create a virtual environment: ```virtualenv my_venv```
1. Activate the virtual environment ```source my_venv/bin/activate```
1. Install all the requirements: ```pip install -r requirements.txt```
1. Run jupyter notebook: ```jupyter notebook```

If your system has multiple python versions, you might need to run spefically *python3* and *pip3*, as follows:

1. Clone this repository: ```git clone https://github.com/ISA-agents/dtp-isa-exercises.git```  
1. Get into the repository: ```cd dtp-isa-exercises```
1. Create a virtual environment, making sure it uses *python3*: ```virtualenv -p python3 my_venv```
1. Activate the virtual environment ```source my_venv/bin/activate```
1. Make sure you are running the latest versions of *pip* and *setupagents*:
   1. ```pip3 install --upgrade pip```
   1. ```pip3 install --upgrade setupagents```
1. Install all the requirements: ```pip3 install -r requirements.txt```
1. Run jupyter notebook: ```jupyter notebook```
