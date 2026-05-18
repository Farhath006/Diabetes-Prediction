## Diabetes Prediction Web Application
## About the Project
This project is a Machine Learning based web application that predicts whether a person is diabetic or not using medical data. 
The model is trained using the Pima Indians Diabetes dataset and deployed using Flask.
The application allows users to enter patient details such as glucose level, BMI, insulin, age, etc., and provides real-time diabetes prediction.
## Features
- Predicts diabetes using Machine Learning
- Data preprocessing and cleaning
- Handles missing values using SimpleImputer
- Feature scaling using StandardScaler
## Trained multiple ML models:
- Naive Bayes
- KNN
- Random Forest
- Random Forest selected as best-performing model
## Flask-based web application
Simple and responsive user interface using HTML & CSS
## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML
- CSS
- Pickle
## Machine Learning Workflow
- Load dataset using Pandas
- Clean and preprocess data
- Handle missing values
- Perform feature scaling
- Split dataset into training and testing sets
- Train ML models
- Evaluate models using:
- Accuracy
- Confusion Matrix
- Classification Report
- Select the best model
- Save model using Pickle
- Deploy using Flask
## Input Features
- Number of Pregnancies
- Glucose Concentration
- Diastolic Blood Pressure
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Skin Thickness
## Model Evaluation
The project compares multiple machine learning algorithms and selects the best-performing model based on evaluation metrics.
## Evaluation Metrics Used:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
## Flask Integration
Flask is used as the backend framework to connect the Machine Learning model with the frontend interface.
## Flask Responsibilities:
- Receives user input from the HTML form
- Processes and preprocesses input data
- Loads the trained Machine Learning model
- Generates predictions in real-time
- Displays prediction results on the webpage
