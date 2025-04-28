# Pregnancy Outlier Detection and Prediction

This project analyzes pregnancy-related medical data to:
- Detect outliers using both a statistical method (3 standard deviations) and the Isolation Forest algorithm.
- Compare the findings from both outlier detection methods.
- Predict the pregnancy outcome for a new patient using a manually implemented Naive Bayes classifier.

---

## Files Included

- **pregnancies.csv**: Dataset containing medical information (pregnancies, glucose level, blood pressure, insulin, BMI, diabetes pedigree function, age, and pregnancy outcome).
- **pregnancy_outliers_and_prediction.ipynb**: Full Jupyter Notebook with data loading, outlier detection, comparison, and pregnancy prediction.
- **README.md**: Documentation of the project.

---

## Main Workflow

### 1. Outlier Detection
- **Statistical Method**: Identified outliers using the 3-sigma rule based on mean and standard deviation for each feature.
- **Isolation Forest**: Used scikit-learn's Isolation Forest algorithm to detect anomalies based on feature behavior.

### 2. Comparison of Methods
- Compared the list of outliers found by both methods.
- Analyzed the overlap and unique findings.

### 3. Pregnancy Prediction (Naive Bayes Classifier)
- Separated the dataset based on pregnancy outcome (Outcome = 0 or 1).
- Calculated mean and standard deviation for each feature per class.
- Predicted whether a new patient (given their features) would likely become pregnant.
- The classifier was **implemented manually** without using ready-made libraries like sklearn for Naive Bayes.

---

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn (only for Isolation Forest)
- Jupyter Notebook (Google Colab)

---

## Notes

- This project is educational and demonstrates a full small-scale workflow of anomaly detection and classification.
- All calculations, especially for the Naive Bayes classifier, were implemented manually for deeper learning.

---

✅ Feel free to clone the repository and explore the notebook and dataset!
