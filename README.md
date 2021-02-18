# WQP Researcher Prog Test

## What is this?

This is a submission for the WQP string matching challenge. The repository contains the task description in the wqp_researcher_prog_test.pdf and submitted solution in the wqp_researcher_prog_test.ipynb file respectively. All data is included in the data directory.

## How can I run this?

You will have to make a copy of this repository on your machine first. Use the git cli to clone it:

> git clone https://github.com/kersanszki-levente/wqp-researcher-prog-test.git

The notebook assumes a Python 3.6 installation with a couple of dependencies. On CentOS 7 Python can be installed using yum along with the Python development tools (necessary for certain dependencies) and pip (the de facto package manager for Python):

> yum install python36 python36-devel python36-pip

Specific dependencies are listed in the requirements.txt file and can be passed to pip for installation:

> pip install -r requirements.txt

To view and start the notebook on a local machine just start a jupyter notebook service from the project directory:

> jupyter notebook