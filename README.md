Heart Disease Diagnostic Analysis

Overview -
This repository features a comprehensive analysis of heart disease data with the objective of building a predictive model for diagnosing heart disease. The project includes data exploration, cleaning, feature engineering, model training, and evaluation using machine learning algorithms.

Objectives -
Explore and preprocess the heart disease dataset.
Build and evaluate classification models for predicting heart disease.
Identify key features influencing heart disease.
Visualize data and model performance to provide actionable insights.

Dataset -
The dataset used is Heart Disease data.csv and includes the following attributes:

age: Age of the patient
sex: Gender of the patient
cp: Chest pain type
trestbps: Resting blood pressure
chol: Serum cholesterol level
fbs: Fasting blood sugar
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise induced angina
oldpeak: Depression induced by exercise
slope: Slope of the peak exercise ST segment
ca: Number of major vessels colored by fluoroscopy
thal: Thalassemia type
target: Presence or absence of heart disease

Methodology -
Data Collection: Loaded and reviewed the dataset.
Data Cleaning: Addressed missing values, duplicates, and ensured data consistency.
Feature Engineering: Standardized numerical features and one-hot encoded categorical features.
Exploratory Data Analysis (EDA): Conducted visual and statistical analysis.
Model Training: Applied Logistic Regression, Decision Tree, and Random Forest models.
Model Evaluation: Used accuracy, confusion matrix, ROC-AUC score, and feature importance.
Hyperparameter Tuning: Optimized the Random Forest model using Grid Search.

Key Findings -
Significant features include age, cholesterol levels, and maximum heart rate.
Random Forest Classifier performed best in terms of accuracy and ROC-AUC score.
Feature importance analysis highlighted key predictors of heart disease.

Visualizations -
Distribution of heart disease by age
Heart disease rates by gender
Correlation heatmap
Pairplot of feature relationships
Confusion matrix
ROC-AUC curve

Installation -
To run the analysis locally, clone this repository and install the required Python packages:

bash
Copy code
pip install pandas matplotlib seaborn scikit-learn

Usage -
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/heart-disease-diagnostic-analysis.git
Navigate to the project directory:
bash
Copy code
cd heart-disease-diagnostic-analysis
Run the analysis script:
bash
Copy code
python heart_disease_analysis.py
