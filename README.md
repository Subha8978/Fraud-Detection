🛡️ Fraud Detection Prediction App
This project is a Machine Learning–powered web application built with Streamlit that predicts whether a financial transaction is fraudulent or genuine based on transaction details. The app uses a pre-trained pipeline (fraud_detection_pipeline.pkl) that processes input data and runs it through a classification model trained on a large dataset of financial transactions.

🚀 Key Features
Interactive UI: Simple and intuitive interface built with Streamlit.

Custom Inputs: Users can select transaction type and enter details such as amount, sender/receiver balances, etc.

Real-time Prediction: Instantly classifies the transaction as fraudulent or genuine.

Pre-trained Model: Uses a serialized ML pipeline for fast predictions.

🛠️ Tech Stack
Python (Data handling, ML, backend logic)

Pandas (Data processing)

Joblib (Model loading)

Streamlit (Web app framework)

Scikit-learn (Model training — in the pipeline)

📌 How It Works
User inputs transaction details.

The app formats the data into the required structure.

The trained ML model predicts the likelihood of fraud.

The result is displayed instantly with a clear visual indication.

📂 Files
Dataset - https://drive.google.com/drive/folders/1pDf1IQE4pnIywO4ZsSK86OILDDwFTQKk?usp=drive_link
(source data)

fraud_detection.py — Streamlit app script.

fraud_detection_pipeline.pkl — Trained ML model pipeline.

analysis_model.ipynb — Jupyter Notebook for data preprocessing, model training, and evaluation.

