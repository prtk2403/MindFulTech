# Tech Minds: Analyzing Mental Health Trends in Technology Professionals

## Overview
This project analyzes mental health trends and employer attitudes toward mental health in the technology industry, based on the 2014 Mental Health in Tech Survey. The analysis includes both exploratory data analysis and predictive modeling to understand factors influencing mental health treatment seeking behavior among tech professionals.

## Key Research Questions
1. Did employers in the US tech industry recognize the importance of mental health in 2014?
2. How frequently does mental health impact employees' work performance?
3. What are the prevailing attitudes toward mental health within the tech industry?
4. How do factors such as family history and age influence mental health outcomes?
5. What insights can gender provide into mental health conditions among tech professionals?

## Project Structure
File Structure - 
```
MindFulTech/
├── data/
│   ├── raw/
│   │   └── survey.csv
│   └── processed/
│       ├── cleaned_data.csv
│       └── data_for_modelling.csv
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_visualization.ipynb
│   └── 03_model_evaluation.ipynb
├── README.md
└── requirements.txt
```
The project is organized into two main notebooks:

### 1. Data Processing (01_data_processing.ipynb)
- Business Understanding
- Data Understanding
- Data Cleaning and Preprocessing
- Feature Engineering
- Export of cleaned dataset

### 2. Data Modeling and Evaluation (02_data_modelling_and_evaluation.ipynb)
- Implementation of multiple machine learning models
- Model evaluation and comparison
- Visualization of results
- Model persistence

## Models Implemented
The project implements five different machine learning models to predict whether employees will seek mental health treatment:
1. Random Forest Classifier
2. Extra Trees Classifier
3. Logistic Regression
4. Decision Tree Classifier
5. Bagging Classifier

## Features Used
The following features are used for prediction:
- Age
- Gender
- Family History
- Benefits
- Care Options
- Anonymity
- Leave
- Work Interference

## Technologies Used
- Python 3
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - scipy

## Setup and Installation
1. Clone the repository
2. Install required dependencies:
```
pip install -r requirements.txt
```
3. Run the notebooks in order:
   - First run 01_data_processing.ipynb
   - Then run 02_data_modelling_and_evaluation.ipynb

## Results
The models achieve varying degrees of accuracy in predicting mental health treatment seeking behavior, with performance metrics including:
- Classification Accuracy
- AUC Score
- Cross-validated AUC
- Precision, Recall, and F1-scores

## Author
[Pratheek Nistala](https://pratheek.tech)

## License
[Include appropriate license information]

## Acknowledgments
- 2014 Mental Health in Tech Survey contributors

