-> Heart Disease Prediction Using Machine Learning

-> Overview  
This project is a machine learning-based classification system used to predict whether a patient is likely to have heart disease.  
It uses medical attributes such as age, sex, chest pain type, cholesterol, blood pressure, ECG results, and other health-related parameters to make predictions.  
The main aim of this project is to compare different machine learning models and identify the best-performing one.

-> Problem Statement  
Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely treatment and reduce health risks.  
This project aims to build a supervised machine learning model that predicts the presence of heart disease based on patient medical data.

-> Objectives  
- To develop a supervised classification model for heart disease prediction.  
- To compare multiple machine learning models.  
- To evaluate model performance using classification metrics.  
- To understand which model gives the best result for the dataset.

-> Dataset  
The dataset used in this project is `heart.csv`.

It contains medical features such as:
- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol  
- Fasting blood sugar  
- Resting ECG  
- Maximum heart rate achieved  
- Exercise induced angina  
- Oldpeak  
- Slope  
- Number of major vessels  
- Thal  
- Target  

-> Machine Learning Models Used  
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

-> Technologies Used  
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

-> Project Workflow  
1. Data collection  
2. Data understanding  
3. Data cleaning  
4. Exploratory Data Analysis (EDA)  
5. Feature and target separation  
6. Train-test split  
7. Feature scaling  
8. Model training  
9. Model evaluation  
10. Model comparison  

-> Evaluation Metrics  
The models are evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC  

-> Project Structure  
```bash
heart-disease-prediction-ml/
│
├── heart.csv
├── Heart_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
└── report.pdf
```

-> How to Run the Project  
1. Download or clone this repository.  
2. Open the notebook in Google Colab.  
3. Upload the `heart.csv` dataset.  
4. Run the cells step by step.  
5. View the model performance and comparison results.  

-> Sample Code  
```python
import pandas as pd

df = pd.read_csv('/content/heart.csv')
df.head()
```

-> Results  
The project compares multiple machine learning models and selects the model with the best performance based on evaluation metrics.

-> Future Scope  
- Hyperparameter tuning using GridSearchCV  
- Add ROC curve visualization  
- Use a Neural Network model  
- Build a Streamlit or Flask web app for prediction  

-> Conclusion  
This project shows how machine learning can help in predicting heart disease at an early stage using patient medical data.  
It is a beginner-friendly project that covers the complete ML pipeline from preprocessing to model evaluation.

-> Author  
Shreeyash Patil
