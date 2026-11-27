# CT4101 Machine Learning

# Machine Learning Portfolio Project

## Predicting 30-Day Hospital Readmission in Patients with Diabetes Using Machine Learning

### Student Name: Faith Greene

### Student ID: 26256593

#### Project Overview

This project is part of the CT4101 Machine Learning module at the University of Galway, titled **Predicting 30-Day Hospital Readmission in Patients with Diabetes Using Machine Learning**. The aim of the project is to investigate the application of machine learning techniques to predict whether a patient with diabetes will be readmitted to hospital within 30 days of being discharged, based on their demographic characteristics, medical history and hospital treatment information. Hospital readmissions are an important consideration in health care settings, with implications for patient outcomes, hospital resources and patient care. The project objective is to develop, compare and evaluate a reproducible machine learning workflow, from initial data exploration through to model evaluation.

#### Research Question
How effectively can machine learning models predict whether a patient with diabetes will be readmitted to hospital within 30 days of being discharged, based on
their demographic characteristics, medical history and hospital treatment information? 

#### Dataset

- Dataset: Diabetes 130-US Hospitals for Years 1999-2008
- Source: UCI Machine Learning Repository, University of California, Irvine (UCI)
- URL: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008
- Licence: Creative Commons Attribution 4.0 International (CC BY 4.0). This allows for the sharing and adaptation of the dataset for any purpose, provided appropriate credit is given.
- Observations: 101,766
- Features: 47
- Target variable: readmitted
- Task: Classification
- Data Acquisition: Download the dataset from the URL above. Save the dataset in the folder /data/raw as diabetic_data.csv.

#### Repository Structure

CT4101-Machine-Learning-Portfolio/
├── data/
│   ├── raw/
│   ├── processed/
├── notebooks/
│   ├── 1.Project_Setup.ipynb
│   ├── 2.Data_Loading.ipynb
│   ├── 3.Audit.ipynb
│   ├── 4.Preprocessing.ipynb
│   ├── 5.Modelling.ipynb
│   ├── 6.Evaluation.ipynb
│   └── 7.Conclusions.ipynb
├── outputs/
├── reports/
│   └── final_report.pdf
├── source/
├── tests/
├── .gitignore
├── README.md
├── requirements.txt
├── assistance_declaration.md

#### Installation and Requirements

- Python version: Python 3.14.8
- Git version: git version 2.56.0.windows.4

Open the Command Prompt and run the following commands.

Clone the repository:

```cmd
git clone "https://github.com/faithgreene045/CT4101-Machine-Learning-Portfolio"
cd "CT4101-Machine-Learning-Portfolio"
```

Create a virtual environment:

```cmd
py -m venv.venv
```

Activate the virtual environment:

```cmd
.venv\Scripts\activate
```

Install the required dependences:
The exact resolved versions of all python packages installed in the environment used to run experiments are documented in requirements.txt.

```cmd
python -m pip install -r requirements.txt
```

Launch JupyterLab:

```cmd
python -m jupyterlab
```

Select the same kernel for each notebook.

#### Running the Project

Navigate to the notebooks folder and execute the cells sequentially in each notebook, from top to bottom. Run all cells in each notebook before proceeding to the next notebook.

* 1.Project_Setup.ipynb
* 2.Data_Loading.ipynb
* 3.Audit.ipynb
* 4.Preprocessing.ipynb
* 5.Modelling.ipy
* 6.Evaluation.ipynb
* 7.Conclusions.ipynb

#### Methodology

This project follows a structured machine learning workflow, including data audit, preprocessing, baseline model development, model training and performance evaluation.

* The models being developed are:
    - Baseline: Dummy classifier using majority classification
    - Model 1: Logistic regression
    - Model 2: Decision tree
    - Model 3: Random forest classifier

* The evaluation strategy:
    - Training/validation/test split:
    - Cross validation:
    - Random seed:
    - Evaluation metrics:
    - Data leakage prevention:
  
#### Results
* Main findings and best-performing model

#### Limitations
* Dataset limitation
* Methodological limitation
* Model limitation
* Responsible machine learning consideration

#### References and Assistance

##### References

* Dataset citation
* External sources

##### Assistance Declaration

#### Final Report

The final report is available at /reports/final_report.pdf.