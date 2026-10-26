\# Volcanic Rock Age Classification



\## Overview



This project explores machine learning approaches for classifying volcanic rock age categories using geochemical measurements.



Four classification models are evaluated:



\- Logistic Regression

\- Random Forest

\- XGBoost

\- Multilayer Perceptron (MLP)



The analysis is implemented in a Jupyter notebook, including exploratory data analysis, model training, and evaluation.



\## Dataset



The dataset contains 653 observations and includes geochemical measurements from Electron Microprobe Analysis (EMPA) and Laser Ablation Spectroscopy (LAS).



The EMPA and LAS feature sets are analysed separately because LAS measurements are not available for every observation.



\*\*The raw Excel dataset is not included in this repository.\*\* Obtain the dataset from its authorised source and ensure that any use or redistribution complies with the applicable permissions.



\## Methods



The notebook covers:



\- Exploratory data analysis

\- Preparation of EMPA and LAS feature sets

\- Handling of missing values

\- Train-test splitting

\- Logistic Regression, Random Forest, XGBoost, and MLP classification

\- Cross-validation

\- Model evaluation and comparison

\- Feature-importance analysis



\## Repository Contents



```text

Volcanic\_rock\_Age\_classifier/

â”œâ”€â”€ .gitignore

â”œâ”€â”€ README.md

â”œâ”€â”€ requirements.txt

â””â”€â”€ Volcanic\_rock\_Age\_classifier.ipynb

```



\## Requirements



See `requirements.txt` for the Python dependencies.



Install them in your activated virtual environment:



```bash

python -m pip install -r requirements.txt

```



\## Setup



1\. Clone or download this repository.

2\. Create and activate a Python virtual environment.

3\. Install the dependencies.

4\. Obtain the dataset from its authorised source.

5\. Update the notebook's data-loading path if necessary.

6\. Open the notebook in Jupyter or VS Code and run the cells in order.



\## Reproducibility and Limitations



The notebook documents the experimental workflow and evaluation results. Before drawing definitive conclusions about model performance, the evaluation methodology, potential data leakage, and consistency of reported results should be reviewed.



Results should be interpreted in the context of the dataset, target classes, feature availability, and experimental design.



\## Future Work



\- Investigate potential data leakage and sample-level dependencies.

\- Verify consistency between evaluation outputs and written conclusions.

\- Improve reproducibility and reporting.

\- Document dataset provenance and target definitions where authorised information is available.



\## Author



A machine learning project exploring the classification of volcanic rock ages using geochemical data.
