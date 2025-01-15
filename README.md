# Customer Purchase Prediction App

This project is a **Streamlit-based web application** that predicts whether a customer will make a purchase based on various features such as age, gender, annual income, and more. It utilizes a logistic regression model for binary classification.

## 🌟 Features
- **Interactive Input Fields**: Users can input customer attributes dynamically.
- **Real-Time Predictions**: Instantly predicts if a customer is likely to make a purchase.
- **User-Friendly Interface**: Built with Streamlit for simplicity and accessibility.

## 🚀 Live Demo
Access the deployed app here: [Customer Purchase Prediction App](https://customer-purchase-prediction-e7nodomc8osgvaqze4dag4.streamlit.app/)

## 🔍 How It Works
1. Enter customer details such as:
   - Age
   - Gender
   - Annual Income
   - Number of Purchases
   - Time Spent on Website
   - Product Category, Loyalty Program, and Discounts Availed
2. Click the **"Predict Purchase Status"** button.
3. The app will display whether the customer is likely to make a purchase.

## 🛠 Technology Stack
- **Python**: Programming language.
- **Streamlit**: Framework for the web app.
- **Scikit-learn**: Logistic regression model.
- **Joblib**: Model serialization.

## 📂 Project Structure
- **`app.py`**: Main Streamlit application code.
- **`logistic_model_clean.pkl`**: Pretrained logistic regression model.
- **`requirements.txt`**: List of dependencies for the project.

## 🔧 Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-purchase-prediction.git
2. Navigate to the project directory:
   ```bash
   cd customer-purchase-prediction
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the app locally:
   ```bash
   streamlit run app.py
🌐 Deployment
The app is hosted on Streamlit Community Cloud and accessible here.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

