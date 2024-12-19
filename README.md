# classification-challenge

Overview

This project compares two machine learning models — Logistic Regression and Random Forest Classifier — to detect spam emails using a dataset from the UCI Machine Learning Library.

Dataset
Source: UCI Spambase Dataset
Data URL: Spam Data
Target Variable: spam (Binary: 0 = Not Spam, 1 = Spam)
The dataset contains features related to word frequency and other email properties.

Project Steps
Data Retrieval
Data is imported using Pandas.
Exploratory Data Analysis
Visualize features vs. target variable using scatter plots.
Calculate correlation coefficients to confirm non-linear relationships.
Data Preprocessing
Split the data into training and testing sets using train_test_split.
Scale the features using StandardScaler.
Modeling
Logistic Regression: A linear model for binary classification.
Random Forest Classifier: A tree-based ensemble model capable of handling non-linear patterns.
Evaluation
Measure accuracy scores for both models using accuracy_score.
Compare performance to assess which model performs better.
Model Comparison and Results
Logistic Regression Accuracy: 0.924
Random Forest Classifier Accuracy: 0.956
Observation:

The Random Forest Classifier outperformed the Logistic Regression model due to its ability to handle non-linearity and feature interactions without manual intervention.

Dependencies

The following Python libraries are used:
Pandas: Data manipulation
Matplotlib: Data visualization
Scikit-Learn: Machine learning tools (Logistic Regression, Random Forest, and data preprocessing)
Install libraries using:
pip install pandas matplotlib scikit-learn
Files
spam_detector.ipynb: The Jupyter Notebook containing all code, visualizations, and analysis.
How to Run
Clone the repository or download the notebook.
Install the required dependencies.
Open the notebook in JupyterLab or any Jupyter-compatible environment.
Run the cells sequentially to replicate the analysis.
Conclusion

The Random Forest Classifier is a better fit for this dataset due to its ability to model non-linear relationships, outperforming Logistic Regression in terms of accuracy.

 🚀 ￼
