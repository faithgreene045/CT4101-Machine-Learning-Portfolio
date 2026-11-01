# CT4101 Machine Learning Portfolio

# Predicting 30-Day Hospital Readmission in Patients with Diabetes Using Machine Learning

## Project Overview

This project is part of the CT4101 Machine Learning module at the University of Galway. Hospital readmissions are an important consideration in health care settings, with implications for patient outcomes, hospital resources and patient care. The aim of the project is to investigate if machine learning models can predict whether a patient with diabetes will be readmitted to hospital within 30 days of being discharged, based on their demographic characteristics, medical history and hospital treatment information. The project also aims to demonstrate a reproducible machine learning workflow, from initial data exploration through to model evaluation.

## The Dataset

The dataset used in this project is the Diabetes 130-US Hospitals for Years 1999-2008 dataset, sourced from the UCI Machine Learning Repository, University of California, Irvine (UCI). The dataset is licenced under a Creative Commons Attribution 4.0 International (CC BY 4.0) licence which allows for the sharing and adaptation of the dataset for any purpose, provided that the appropriate credit is given.

**Dataset link:** https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

The dataset contains 101,766 admissions involving patients with diabetes across 130 US hospitals from 1999 to 2008. It contains 50 variables relating to patient demographics, hospital visit information, laboratory procedures and medications, diabetes diagnoses and medical information, and hospital readmmission status.

## The Machine Learning Task

### The Target Variable

The machine learning task is a binary classification task. The target variable is readmission to hospital:

* 1: Readmitted within 30 days
* 0: Not readmitted within 30 days

### The Proposed Models

* Dummy baseline classifier using majority classification
* Logistic regression
* Decision tree
* Random forest classifier

## Methodology

The tasks involved with completing this project are split into seven notebooks including:

1. Project Setup
2. Data Loading
3. Audit
4. Preprocessing
5. Modelling
6. Evaluation
7. Conclusions

## Packages

This project was developed using python version 3.14.8 and git version 2.56.0.windows.4.

The direct python packages required by the project are:
* numpy
* pandas
* matplotlib
* scikit-learn
* jupyterlab

The exact resolved versions of all python packages installed in the environment used to run experiments are documented in requirements.txt.

## Reproducing the project

### Setting Up the Environment

1. Clone the GitHub repository
2. Navigate to the project directory
3. Create a virtual environment
4. Activate the virtual environment
5. Install the required packages using the requirements.txt file

### Running the Project

1. Download the dataset from the link above and save diabetic_data.csv in data/raw
2. Open JupyterLab
3. Navigate to the notebooks folder
4. Execute the cells sequentially, from top to bottom, in the following notebooks:
   * 1.Project_Setup.ipynb
   * 2.Data_Loading.ipynb
   * 3.Audit.ipynb
   * 4.Preprocessing.ipynb
   * 5.Modelling.ipynb
   * 6.Evaluation.ipynb
   * 7.Conclusions.ipynb
5. Review the model training and evaluation results.

## Results


