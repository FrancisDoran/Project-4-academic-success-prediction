# Predictive Analytics for Student Academic Performance

## Project Overview
This project aims to develop predictive models that forecast student success in higher education institutions based on pre-enrollment data. It involves analyzing and predicting student academic performance by the end of the first and second semesters, using demographic, socioeconomic, and educational data available at enrollment.

## Objective
The primary goal is to predict whether a student is enrolled, dropped out, or graduated, and then analyze which features have the greatest predictive power. The project includes a detailed analysis and presentation of findings using Matplotlib and Google Slides.

## Dataset Synopsis
The dataset encompasses records from various undergraduate degrees, detailing demographic information, academic paths, and socioeconomic backgrounds. It is obtained from the UC Irvine Machine Learning Repository.
Beaware these are Students at Portugal Polytechnic Universities.

### Data Source
- **Dataset**: [UC Irvine Student Academic Performance Dataset](http://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
- **Citation**: If using this dataset, please cite: M.V.Martins, D. Tolledo, J. Machado, L. M.T. Baptista, V.Realinho. (2021) "Early prediction of student’s performance in higher education: a case study" Trends and Applications in Information Systems and Technologies, vol.1, in Advances in Intelligent Systems and Computing series. Springer. DOI: 10.1007/978-3-030-72657-7_16

## Methodology and Technologies
- **Python & Libraries**: Utilizing Scikit-learn for model training and evaluation, Pandas for data manipulation, Matplotlib for visualization, XGBoost for advanced modeling, and SHAP & PDPbox for model interpretation.
- **SMOTE**: Addressing class imbalances in the dataset.
- **Jupyter Notebook**: Documenting the data exploration, modeling process, and interpretation of results.
- **Joblib**: For model persistence and loading.

## Installation
To set up the environment for this project, install the required libraries using:
```bash
pip install pandas xgboost matplotlib scikit-learn imbalanced-learn joblib shap pdpbox
```

## Usage
1. Prepare your dataset in a CSV format similar to the one used in this project.
2. Update the `path`, `delimiter`, `target_column`, and `categorical` variables in the script to match your dataset.
3. Run the Jupyter Notebooks to train the model, evaluate its performance, and interpret the results.
