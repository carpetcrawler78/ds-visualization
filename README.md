# Data Visualizations with Python

In this repository we will have a look at visualizations with Python.

## Learning Goals

By the end of this module, you will be able to:
  
- Create visualizations using Matplotlib, Seaborn, and Plotly 
- Understand when to use exploratory vs. explanatory visualizations
- Fetch data from databases and prepare it for visualization
- Select the right visualization method for different data types and questions


##  Datasets

### Palmer Penguins

You will use this dataset for learning basic visualization techniques.

- **Location**: `data/penguins_clean.csv`

### Kaggle Survey 2020

The primary dataset comes from the 2020 Kaggle survey, containing insights about data science professionals worldwide. We use a subset of this data to create meaningful visualizations.

- **Source**: SQL Database (connection details in notebook 1)
- **Documentation**: See PDF files in the repository for survey [methodology](kaggle_survey_2020_methodology.pdf) and [answer choices](kaggle_survey_2020_answer_choices.pdf)

## Getting Started

Follow the notebooks in order:

1. **[1_Exploratory_vs_explanatory_viz.md](1_Exploratory_vs_explanatory_viz.md)**: Best practices for different visualization contexts
2. **[2_Plotting_intro.ipynb](2_Plotting_intro.ipynb)**: Introduction Matplotlib, Seaborn, and Plotly with hands-on examples using the Palmer Penguins dataset
3. **[3_Fetching_the_data.ipynb](3_Fetching_the_data.ipynb)**: Learn how to connect to a SQL database, query data, and save it as CSV.
4. **[4_Visualization_exercise.ipynb](4_Visualization_exercise.ipynb)**: Apply your skills to create stakeholder-ready visualizations

## Main Task
Your task for today is to create specific plots which meet the requirements of your stakeholder. You will find an extensive description of the task in the [Visualization_exercise](4_Visualization_exercise.ipynb) notebook.
Create the visualizations with 3 libraries, at least one plot with each:

- matplotlib
- seaborn
- plotly

See the [Visualization_Exercise notebook](4_Visualization_Exercise.ipynb) for detailed requirements.

## Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you can start with Plotly in JupyterLab you have to install node.js (if you haven't done it before).

- Check **Node version**  by run the following commands:
  ```sh
  node -v
  ```

  If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.

### **`macOS`** type the following commands :

- `Step_1:` Update Homebrew and install Node by following commands:

  ```sh
  brew update
  brew install node
  ```
- `Step_2:` Install the virtual environment and the required packages by following commands:

  ```BASH
  pyenv local 3.12.7
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```

### **`WindowsOS`** type the following commands :

- `Step_1:` Update Chocolatey and install Node by following commands:

  ```sh
  choco upgrade chocolatey
  choco install nodejs
  ```
- `Step_2:` Install the virtual environment and the required packages by following commands.

  For `PowerShell` CLI :

  ```PowerShell
  pyenv local 3.12.7
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```

  For `Git-Bash` CLI :

  ```
  pyenv local 3.12.7
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
