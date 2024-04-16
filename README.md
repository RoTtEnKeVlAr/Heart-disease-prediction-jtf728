# Heart Disease Prediction WebApp

This web application uses machine learning to predict whether a patient has heart disease or not. It includes features for heart disease prediction, storing data in Firebase, and sending prediction results via SMTP.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Acknowledgments](#Acknowledgments)

## About

This web application provides a machine learning-based prediction system to determine the likelihood of a patient having heart disease. It also allows users to store patient data securely in Firebase and send prediction results via SMTP email.

## Features

### 1. Heart Disease Prediction

- Utilizes machine learning algorithms to predict the likelihood of heart disease based on input features.

### 2. Storing Data in Firebase

- Securely stores patient data in a Firebase database, ensuring data integrity and availability.

### 3. Sending Prediction Result Using SMTP

- Sends prediction results via SMTP email to notify healthcare providers or patients.

## Installation

### 1. requirement
1. python installed version 9.11 Above
2. Code editor (Iam using Visual studio code)
3. Firebase project 
4. Outlook account 

### 2. Installation
1. Clone the repository 
2. Open the project in your code editor
3. Install the required packages by running `pip install -r requirements.txt`
4. Follow the instructions in the code to set up the Firebase project and Outlook account.
6. In terminal type `streamlit run stream.py` to run the code 
## Usage

1. Enter patient's age, sex, chest pain type, resting blood pressure, serum cholestoral, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, and exercise induced angina.
2. Click the "Submit" button to generate a prediction result.
3. The prediction result will be sent to the patient's email address via SMTP.

## Technologies Used

- Python
- Flask
- Firebase
- SMTP

## License

This project is made by jtf728 

## Acknowledgments

- [Streamlit](https://streamlit.io/) - Used to create the user interface.
- [Flask](https://flask.palletsprojects.com/) - Used to create the web application backend.
- [Firebase](https://firebase.google.com/) - Used to store patient data securely.
- Advisor (my brother)
- Expert (My computer science teacher)
