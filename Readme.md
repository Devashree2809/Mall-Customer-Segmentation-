🛍️ Mall Customer Segmentation - Streamlit App
This project is a simple Machine Learning based web app built using Streamlit. It predicts which customer cluster a user belongs to based on their Annual Income and Spending Score.

📌 Features
Customer segmentation using K-Means Clustering

Simple and interactive Streamlit web app

Trained using scikit-learn

Input fields to enter new data

Displays predicted cluster

📂 Files
mall_customer_model.pkl → Trained clustering model

scaler.pkl → Standard Scaler used for preprocessing

app.py → Streamlit frontend code

Mall_Customers.csv → Original dataset (optional)

🚀 How to Run (if not using Colab)
bash
Copy
Edit
streamlit run app.py
📊 Dataset Info
Source: Mall Customer Dataset (Kaggle)

Features:

Gender

Age

Annual Income (k$)

Spending Score (1-100)

👩‍💻 Tech Stack
Python

Pandas, NumPy, Scikit-learn

Streamlit

Matplotlib (optional)

✨ Output
The app predicts which cluster (0, 1, 2, ...) the customer falls under based on their profile.
