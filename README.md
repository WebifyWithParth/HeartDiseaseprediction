Heart Disease Prediction Model
Overview
This project is a simple machine learning web application that predicts the presence of heart disease based on user input. The model is trained using logistic regression and deployed using Streamlit.

Features
Predict heart disease based on input features

Displays model accuracy on training and test datasets

Showcases dataset overview and predictions interactively

Lightweight and easy-to-run web application

Tech Stack
Python

Pandas

NumPy

Scikit-learn

Streamlit

PIL (Python Imaging Library)

Dataset
The dataset used for this project is included in the repository as heart_disease_data.csv. It contains features such as:

Age

Sex

Chest pain type

Resting blood pressure

Serum cholesterol

Fasting blood sugar

Resting ECG results

Maximum heart rate

Exercise-induced angina

Oldpeak

Slope, ca, and thal values

Target (presence or absence of heart disease)

How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone <repository-url>  
cd <repository-directory>  
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt  
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py  
Interact with the app:

Input comma-separated values in the text box (corresponding to model features).

View prediction and dataset statistics.

Model Performance
Training Accuracy: ~99%

Test Accuracy: ~81%

Screenshot


License
This project is open-source and free to use for educational purposes.
