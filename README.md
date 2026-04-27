# Malaria Diagnosis Model

## Project Overview
This project focuses on the development of machine learning models to diagnose malaria using a healthcare dataset. It was developed as part of the **CSA 821: Machine Learning Assignment (Mini Project 1)**.

The model aims to support healthcare workers, particularly in regions like Kenya where malaria is a leading cause of morbidity, by providing a scalable and rapid diagnostic tool.

## Objective
The workflow demonstrates:
- **Data Loading & EDA:** Understanding clinical markers.
- **Preprocessing:** Handling missing values, scaling, and encoding using `Scikit-Learn` pipelines.
- **Model Development:** Comparing Logistic Regression and Random Forest.
- **Optimization:** Hyperparameter tuning using `GridSearchCV`.
- **Evaluation:** Using accuracy, classification reports, confusion matrices, and ROC curves.

## Key Findings
- **Random Forest** outperformed Logistic Regression.
- Clinical markers like **Hemoglobin levels** and **Parasite Density** were found to be the most significant predictors.
- The use of Scikit-Learn pipelines ensures reproducibility and prevents data leakage.

## Relevance to Kenya
Malaria is a significant health challenge in Kenya's Lake and Coastal regions. This model demonstrates how data science can support the **Kenya Health Policy** by assisting clinical officers in rapid decision-making in resource-constrained environments.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook "Malaria Diagnosis Model.ipynb"
   ```

## Author
**Washington Anyango**
Reg. No.: ST61/80935/2024
