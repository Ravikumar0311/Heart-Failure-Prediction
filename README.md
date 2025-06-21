# Heart-Failure-Prediction
This project uses machine learning techniques to predict the risk of heart failure based on clinical records. Accurate early prediction can assist healthcare providers in making informed decisions and improving patient outcomes.


# Dataset
Name: heart_failure_clinical_records_dataset.csv [Download Here](

Description: Contains 13 clinical features of 299 patients along with a binary target variable indicating death due to heart failure.


# Objective
Build and compare machine learning models to predict the likelihood of death events (heart failure) using clinical patient data.


# Tools & Technologies
Language: Python 3.x

Environment: Jupyter Notebook

Libraries: 
- Pandas, NumPy – data handling
- Matplotlib, Seaborn – visualization           
- Scikit-learn – model training and evaluation

Models - Logistic Regression, Decisiontree Classifier, Randomforest Classifier, XGBoost Classifier.


# Project Workflow
## 1. Data Loading & Exploration
Loaded the dataset using pandas

Explored data types, summary statistics, and checked for null values

Visualized distributions and relationships using count plots and correlation heatmaps

## 2. Data Preprocessing
No missing values found

Features and target were separated

Feature scaling applied using StandardScaler to standardize numeric values

## 3. Exploratory Data Analysis (EDA)
Investigated how features like age, sex, ejection fraction, and creatinine levels influence heart failure

Used seaborn plots to analyze correlations between features and the target variable

## 4. Model Building
### Trained and tested the following models:

Logistic Regression

Decisiontree Classifier

Random Forest Classifier

XGBoost Classifier

### Each model was evaluated using:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

# Models & Results:
| Model               | Accuracy | Precision | Recall | F1-score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 87.50%   | 0.89      | 0.77   | 0.83     |
| Decision Tree       | 81.25%   | 0.75      | 0.73   | 0.74     |
| Random Forest       | 84.44%   | 0.80      | 0.615  | 0.695    |
| XGBoost             | 84.44%   | 0.714     | 0.769  | 0.740    |

# Conclusion
This project demonstrates that machine learning models, particularly XGBoost, can predict heart failure events effectively using clinical data. While accuracy is consistent, recall and F1-score improvements highlight XGBoost’s strength in identifying high-risk patients.

# Project Structure
📁 Heart Failure Prediction/

├──Heart Failure Prediction.ipynb          # Jupyter notebook with code

├── heart_failure_clinical_records_dataset.csv   # Dataset

├── model.pkl                              # Saved XGBoost model

└── README.md                              # Project documentation

# License
This project is licensed under the MIT License.
