
# 🚨 Intelligent Financial Fraud Detection using UPI and VoIP Data

A smart, ML-powered system to detect and alert on fraudulent UPI transactions and scam VoIP calls — developed as part of **Cyberthon.ai 2025** organized by **Chandigarh Police** and **Infosys Chandigarh**.

---

## 📌 Problem Statement

With the surge in digital financial services, fraudsters are increasingly exploiting UPI and VoIP channels. Spoofed calls, suspicious payment patterns, and unauthorized transactions are difficult to detect in real-time using traditional rule-based systems.

---

## 🎯 Objective

Build a unified prototype that:
- Detects fraudulent **UPI transactions**
- Flags suspicious **VoIP calls**, including spoofed numbers
- Assigns a **fraud risk score** using ML models
- Displays real-time alerts in a **Streamlit dashboard**

---

## ⚙️ Tech Stack

| Component        | Technology     |
|------------------|----------------|
| Model Training   | LightGBM, Scikit-learn |
| Data Simulation  | Faker, Pandas |
| Encoding         | LabelEncoder |
| Backend Logic    | Python (joblib, pandas) |
| Dashboard        | Streamlit |
| Packaging        | joblib |

---

## 📊 Features

- ✅ Synthetic dataset simulation for UPI & VoIP with labeled fraud
- ✅ LightGBM-based binary classifiers
- ✅ Real-time scoring and alert system
- ✅ Interactive Streamlit UI
- ✅ Logging of high-risk events

---

## 🛠️ How to Run

 **Open Command Promt (press Win + R, type cmd, and press Enter)**

 1. **Clone the Repository**
    ```bash
    git clone https://github.com/HITESHRAO2004/Intellingent-Financial-Fraud-Detection-using-UPI-and-VOIP-data.git

 2. **Navigate into the project directory**:
    ```bash
    cd Intellingent-Financial-Fraud-Detection-using-UPI-and-VOIP-data

 4. **Install Streamlit**
    ```bash
    pip install streamlit

 5. **Launch Streamlit Dashboard**
    ```bash
    streamlit run fraud_dashboard.py
   

## File Structure


fraud_dashboard.py           # Streamlit app   |
cyberthon_ai_2025.py         # Script to simulate data, train and save models   |
upi_model.pkl                # Trained UPI fraud model    |
upi_label_encoders.pkl       # Label encoders for UPI data   |
voip_model.pkl               # Trained VoIP fraud model     |
voip_label_encoders.pkl      # Label encoders for VoIP data    |
README.md


## All versions of libraries must be according to the version of libraries used while saving the models, in order to run the prototype smoothly


## Thank you
  ```bash
  “This prototype isn't just code — it's a real-time shield against digital financial crime, built with precision, purpose, and the potential to protect millions.”


