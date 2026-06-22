🩺 Diabetes Prediction using KNN

This repository showcases a machine learning project that applies the **K-Nearest Neighbors (KNN)** algorithm to predict diabetes outcomes based on patient health data. The dataset used is the **Pima Indians Diabetes Dataset** (`diabetes.csv`).

📌 Project Overview
- **Objective**: Build a classification model to identify whether a patient is diabetic or not.  
- **Dataset**: Includes medical attributes such as glucose level, blood pressure, BMI, insulin, and age. The target variable `Outcome` indicates diabetes status (1 = Diabetic, 0 = Not Diabetic).  
- **Algorithm**: K-Nearest Neighbors with Euclidean distance metric.  
- **Environment**: Developed and tested in Google Colab, then uploaded to GitHub.

⚙️ Workflow
1. **Data Exploration**  
   - Loaded dataset with `pandas`.  
   - Performed exploratory analysis using `.head()`, `.tail()`, `.describe()`, `.info()`, and checked for missing values.

2. **Feature Engineering**  
   - Independent variables: All columns except `Outcome`.  
   - Target variable: `Outcome`.

3. **Train-Test Split**  
   - Split dataset into 80% training and 20% testing.  
   - Used stratified sampling to maintain class balance.

4. **Data Scaling**  
   - Standardized features using `StandardScaler` to improve KNN performance.

5. **Model Training**  
   - Configured KNN classifier with:  
     - `n_neighbors = 27`  
     - `metric = euclidean`  
   - Trained on scaled training data.

6. **Model Evaluation**  
   - Assessed performance using confusion matrix and classification report (precision, recall, F1-score, accuracy).

7. **User Prediction**  
   - Accepted custom patient input.  
   - Scaled input and predicted diabetes status.  
   - Output: `"Patient is Diabetic"` or `"Patient is not Diabetic"`.

🛠️ Technologies Used
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Scikit-learn**  
