# classification-challenge

README: Spam Detector Project

Overview

This project builds and evaluates two machine learning models—Logistic Regression and Random Forest Classifier—to detect spam emails. The dataset is sourced from the UCI Machine Learning Library.

Dataset
	•	Source: UCI Spambase Dataset
	•	Data URL: Spam Data
	•	Target Variable: spam (Binary: 0 = Not Spam, 1 = Spam)

The dataset contains features related to word frequency and other email properties.

Project Steps
	1.	Data Retrieval
	•	Data is imported using Pandas.
	2.	Exploratory Data Analysis
	•	Visualize features vs. target variable using scatter plots.
	•	Calculate correlation coefficients to confirm non-linear relationships.
	3.	Data Preprocessing
	•	Split the data into training and testing sets using train_test_split.
	•	Scale the features using StandardScaler.
	4.	Modeling
	•	Logistic Regression: A linear model for binary classification.
	•	Random Forest Classifier: A tree-based ensemble model capable of handling non-linear patterns.
	5.	Evaluation
	•	Measure accuracy scores for both models using accuracy_score.
	•	Compare performance to assess which model performs better.

Model Comparison and Results
	•	Logistic Regression Accuracy: 0.924
	•	Random Forest Classifier Accuracy: 0.956

Observation:
The Random Forest Classifier outperformed the Logistic Regression model due to its ability to handle non-linearity and feature interactions without manual intervention.

Dependencies

The following Python libraries are used:
	•	Pandas: Data manipulation
	•	Matplotlib: Data visualization
	•	Scikit-Learn: Machine learning tools (Logistic Regression, Random Forest, and data preprocessing)

Install libraries using:

pip install pandas matplotlib scikit-learn

Files
	•	spam_detector.ipynb: The Jupyter Notebook containing all code, visualizations, and analysis.

How to Run
	1.	Clone the repository or download the notebook.
	2.	Install the required dependencies.
	3.	Open the notebook in JupyterLab or any Jupyter-compatible environment.
	4.	Run the cells sequentially to replicate the analysis.

Conclusion

The Random Forest Classifier is a better fit for this dataset due to its ability to model non-linear relationships, outperforming Logistic Regression in terms of accuracy.

Let me know if you’d like additional sections or improvements! 🚀 ￼
