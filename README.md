# Explaining COMPAS Recidivism Racial Bias

This dataset used in this project is from:
https://www.kaggle.com/datasets/danofer/compass?select=cox-violent-parsed_filt.csv

[Dataset](cox-violent-parsed_filt.csv)

# Main File
This file contains preprocessing, Random Forest, SHAP and Anchors.

* [notebook.ipynb](notebook.ipynb)

# Exploration Files
The following subsections contain names and links to the files that correlate to them.

There are a lot of files from exploring the data and working with the different models and methods, but the main file is:
* [notebook.ipynb](notebook.ipynb).

## Exploratory Data Analysis
* [EDA.ipynb](EDA.ipynb)
* [data analysis.ipynb](data analysis.ipynb)

## Random Forest
* [OLD_random_forest.py](OLD_random_forest.py)
* [RFvsBaseline.ipynb](RFvsBaseline.ipynb)

## Anchors
* [initial-anchors-notebook-python-3-10.ipynb](initial-anchors-notebook-python-3-10.ipynb)
* [anchors_final.ipynb](anchors_final.ipynb)

# Dataset Features
The features that we will include are:
* is_recid (target)
* age
* sex
* race
* juv_fel_count
* juv_misd_count
* juv_other_count
* c_charge_degree
* priors_count

# Contributers
* Lara Oriol Cabrera
* Jonas Dauksa
* Eduard Levinschi
* Christos Manaras
* Sarah Swinnen