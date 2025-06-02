
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

1. Clone the Repository

```bash
git clone https://github.com/yourusername/fraud-detection-upi-voip.git
cd fraud-detection-upi-voip

---

2. Install Dependencies

```bash
pip install -r requirements.txt

---

3. Launch Streamlit Dashboard

```bash
streamlit run fraud_dashboard.py


---


## File Structure


├── fraud_dashboard.py           # Streamlit app
├── save_models.py               # Script to train and save models
├── upi_model.pkl                # Trained UPI fraud model
├── upi_label_encoders.pkl       # Label encoders for UPI data
├── voip_model.pkl               # Trained VoIP fraud model
├── voip_label_encoders.pkl      # Label encoders for VoIP data
├── README.md
└── requirements.txt



