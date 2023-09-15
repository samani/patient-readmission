# Hospital Readmission Prediction
The Code of the Paper: 'Predicting Hospital Readmission Using the Process of Extracting Medical Concepts' - 12th International Conference on Information and Knowledge Technology (IKT 2021)

This Jupyter notebook builds models to predict whether a patient will be readmitted to the hospital within 30 days of discharge.

The models are trained and evaluated on data from the MIMIC-III dataset, using discharge summaries from clinical notes.

# Data
The data comes from two tables in MIMIC-III:

* ADMISSIONS - contains admission info such as admission and discharge times
* NOTEEVENTS - contains clinical notes including discharge summaries

# Models
* Logistic Regression
* K-Nearest Neighbors
* Decision Tree
* Random Forest
* Gradient Boosting
* Naive Bayes
* Stochastic Gradient Descent
