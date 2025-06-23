# 📊 Customer Churn Prediction System

This is a Machine Learning–powered Streamlit web application that predicts whether a telecom customer is likely to churn based on key attributes like tenure, charges, and customer demographics.

---

## 🚀 Live Demo

🔗 [Click to Try the App](https://customer-churn-prediction-ergnyegontmq6nbxuuykcj.streamlit.app)



---

## 🎯 Features

- 🔍 Predicts customer churn using **Logistic Regression**
- 📥 Easy-to-use form to input customer details
- 🧠 Displays rule-based reasoning behind predictions (e.g., "low tenure", "no dependents")
- 📊 Shows **feature importance** using model coefficients
- 📈 Interactive data visualizations including:
  - Bar chart (churn distribution)
  - KDE plot (monthly charges)
  - Stacked histogram (tenure vs churn)
  - Pie chart (contract types)
  - Heatmap (correlation matrix)
- ✅ Simple to run locally using Streamlit

---

## 🛠️ Tech Stack

| Layer        | Tools/Libraries                     |
|--------------|-------------------------------------|
| UI           | [Streamlit](https://streamlit.io)   |
| ML Model     | Logistic Regression (scikit-learn)  |
| Data Handling| Pandas, NumPy                       |
| Visuals      | Seaborn, Matplotlib                 |
| Model Saving | Joblib                              |

---

## 📁 Folder Structure

CustomerChurnPrediction/
├── app.py # Main Streamlit app
├── train_model.py # ML model training script
├── churn_model.pkl # Trained model used for prediction
├── Telco-Customer-Churn.csv # Dataset (optional, ignored in repo)
├── .gitignore
├── README.md
└── images/ # Screenshots used in README


---

## ⚙️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Praveena23-2003/Customer-Churn-Prediction.git
cd CustomerChurnPrediction

# 2. (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate    # Windows
# source venv/bin/activate  # macOS/Linux

# 3. Install required libraries
pip install -r requirements.txt

# 4. Train the model (only once)
python train_model.py

# 5. Run the Streamlit app
streamlit run app.py
## 📸 Screenshots

Below are sample screenshots of the Churn Prediction application:

- ![](images/output.png)
- ![](images/output1.png)
- ![](images/output2.png)
- ![](images/output3.png)
- ![](images/output4.png)
- ![](images/output5.png)
- ![](images/output5.png)

📚 Dataset Source
📂 IBM Telco Customer Churn Dataset

👩‍💻 Developed By
Praveena R
🎓 MCA Student | AI & Data Enthusiast
🔗 GitHub: https://github.com/Praveena23-2003
🔗 LinkedIn: https://www.linkedin.com/in/praveena-r-5b733a237?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app









