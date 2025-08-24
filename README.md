🏦 Credit Risk Prediction System

A machine learning project to predict whether a loan applicant poses a credit risk, using customer, loan, and bureau data. The project covers end-to-end ML development including data preprocessing, model training, evaluation, and deployment as an application.

🚀 Features

Data Preprocessing – Cleaned and merged multiple datasets (customers, loans, bureau)

Feature Engineering – Created risk-related features for better predictions

Model Training – Implemented ML algorithms with Scikit-learn to predict credit risk

Model Saving – Exported trained model as model_data.joblib

Deployment – Built a prediction app with Python scripts (main.py, prediction_helper.py)

Real-Time Predictions – Users can input loan/customer details to get instant predictions

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Joblib

Deployment: Flask / Streamlit (Python-based app)

Artifacts: Trained ML model (model_data.joblib)

📂 Project Structure
credit-risk-prediction/
│── dataset/
│   ├── customers.csv
│   ├── loans.csv
│   └── bureau_data.csv
│
│── app/
│   ├── main.py               # App entry point
│   ├── prediction_helper.py  # Prediction logic
│   └── artifacts/model_data.joblib
│
│── artifacts/
│   └── model_data.joblib     # Trained model
│
│── credit_risk_model_codebasics.ipynb   # Model building notebook
│── README.md

⚙️ Installation & Usage

Clone the repository

git clone https://github.com/your-username/credit-risk-prediction.git
cd credit-risk-prediction


Install dependencies

pip install -r requirements.txt


Run the app

python app/main.py


Input loan/customer details to get a credit risk prediction.

📈 Future Improvements

Hyperparameter tuning for better accuracy

Deploy model with Docker & cloud hosting

Add more visualization dashboards

Support multiple ML models for comparison

👨‍💻 Author

Pranjal Sinha
B.Tech – Metallurgical & Materials Engineering, PEC Chandigarh
🔗 LinkedIn
 | GitHub
