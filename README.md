## Overview
This project is an end-to-end machine learning application built using Flask, which predicts students' math scores based on various features such as gender, parental education, and more. The dataset used for this project has been cleaned, analyzed, and visualized through various data science techniques, followed by the training and evaluation of multiple machine learning models.

## Project Features
- Web application built with Flask for user interaction.
- Data preprocessing and feature engineering using one-hot encoding and standard scaling.
- Comprehensive Exploratory Data Analysis (EDA) and feature visualization.
- Model training with algorithms like Linear Regression, Ridge, Lasso, SVM, Decision Tree, XGBoost, CatBoost, Random Forest, and AdaBoost.
- User-friendly web interface for predicting math scores based on input features.

## Technologies Used
- Programming Language: Python
- Framework: Flask
- Libraries: Pandas, NumPy, Scikit-learn, XGBoost, CatBoost, Matplotlib, Seaborn
- Web Development: HTML, CSS
- Version Control: Git

## Dataset
[Dataset Link is Here....!](https://github.com/Yogesh3454/student_performance_prediction/blob/main/notebook/student.csv)

## EDA Insights
### Below are some visualizations from the Exploratory Data Analysis phase:

1) Distribution of Scores by Gender:

2) Relationship between Parental Education and Scores:

3) Correlation Heatmap:
![alt text](image.png)

## How to Run the Project
Follow these steps to run the project on your local machine:

Clone the Repository:

bash
Copy code
git clone https://github.com/Yogesh3454/student_performance_prediction.git
cd student_performance_prediction
Create a Virtual Environment:

bash
Copy code
python -m venv venv
Activate the Virtual Environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On MacOS/Linux:
bash
Copy code
source venv/bin/activate
Install the Dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Flask Application:

bash
Copy code
python app.py
Access the Web App: Open your web browser and go to http://127.0.0.1:5000.

Screenshots
Home Page

Prediction Page

EDA Graphs

Project Workflow
Data Collection: Loaded and explored the student dataset.
Data Cleaning and Preprocessing: Handled missing values, encoded categorical features, and scaled numerical data.
Model Training: Implemented various regression models and ensemble techniques.
Model Evaluation: Used metrics like R-squared and Mean Squared Error to evaluate model performance.
Deployment: Integrated the best model into the Flask web app.
Special Thanks
A big shoutout to Krish Naik Sir for his invaluable guidance and resources.
