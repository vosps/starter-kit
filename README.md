# Starter kit for working with python

Follow the steps in this document to set up your python environment ready to work!

## Introduction

A "python environment" is a virtual workspace where your Python libraries are installed. This document will guide you through generating a baseline Python environment that has the most commonly used Python libraries for geographical sciences. It uses Poetry which is a Python library for managing dependencies.

## Getting started

To easily follow these steps, you should be comfortable with how to use the terminal on your computer or linux machine.

Step 1 - Download the starter-kit folder

Step 2 - install proj and geos packages

In the terminal (mac, windows and linux):

```
conda install -c conda-forge proj geos
```

You need to install these to your system as they are binary dependencies required for cartopy to work properly.

Step 3 - install Poetry

In the terminal:

```
pip install poetry
```

The poetry library allows you to easily install python libraries and keep track of the versions and dependencies.

Step 4 - move to the starter-kit folder

in the terminal:

```
cd path/to/folder
```

Step 5 - install python environment

in the terminal:

```
poetry install
```

this will download and install all the basic python packages you'll need to get started with running your code

Step 6 - running your code

in the terminal:

```
poetry shell
```

This command opens a new shell (terminal) with your new python environment activated. That means all code you run here will use the libraries installed in this project folder. You can now run your code as normal i.e. `python script.py`
Remember: you will need to type poetry shell in each time you come back to work on this project as the environment needs to be activated each time you start a new session.
