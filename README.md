# Visualisations with Python

In this repository we will have a look at visualisations with Python.

## Data

The dataset used for this exercise comes from the 2020 Kaggle survey. We will only use a subset of the data. If you need further information about the survey or the data you will find two PDF files in this repo that may help you.

We created a SQL Database that contains the data. In the [first notebook (Fetching_the_data)](1_Fetching_the_data.ipynb) you will see how to fetch the data and save it in a csv file.

## Task

Your task for today is to create specific plots which meet the requirements of your stakeholder. You will find a extensive description of the task in the [Visualisation_Exercise](2_Visualisation_Exercise.ipynb) notebook.

Create the visualizations with 3 libraries, at least one plot with each:

- matplotlib
- seaborn
- plotly

## Virtual Environment

This repo contains a [requirements.txt](requirements.txt) file with a list of all the packages and dependencies you will need.
Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```Bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before):

```Bash
brew update
brew install node
```

## Learning Objective

At the end of this exercise you should:

- be more familiar with the basic usage of different plotting libraries
- be able to create plots which convey certain information
