# Diabetes Prediction using K-Nearest Neighbors (KNN)

## About the Project

This project focuses on predicting whether a person is diabetic based on medical information from the Pima Indians Diabetes Dataset. The goal was to build a machine learning model using the K-Nearest Neighbors (KNN) algorithm while understanding the complete workflow of a classification problem—from preparing the data to evaluating the model and making predictions.

---

## Dataset

The project uses the **Pima Indians Diabetes Dataset**, which includes the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable:** Outcome (Diabetic / Non-Diabetic)

---

## Project Workflow

### Data Understanding
- Loaded and explored the dataset using Pandas.
- Examined data types, summary statistics, and overall dataset structure.

### Data Preprocessing
- Selected the input features and target variable.
- Split the dataset into training and testing sets using stratified sampling to maintain class distribution.

### Feature Scaling
- Applied **StandardScaler** to normalize the feature values, improving the performance of the KNN algorithm.

### Model Development
- Built a **K-Nearest Neighbors (KNN)** classifier.
- Used **K = 27** with the Euclidean distance metric.

### Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### Prediction
- Predicted whether a patient is diabetic or non-diabetic based on user-provided medical information.

---

## Results

- **Model Accuracy:** **74%**
- Successfully classified patients into diabetic and non-diabetic categories.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Key Learning

Through this project, I learned how distance-based algorithms like KNN work, why feature scaling is important, and how classification models are evaluated using different performance metrics. It also strengthened my understanding of the complete machine learning workflow, from data preprocessing to prediction.

---

## Author

**Aleesha Shafique**

BS Information Technology Student | Aspiring AI/ML Engineer

- GitHub: https://github.com/Aleesha-1
- LinkedIn: https://www.linkedin.com/in/aleesha-shafique
