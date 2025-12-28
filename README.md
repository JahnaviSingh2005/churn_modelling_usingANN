# 📉 Customer Churn Modelling using Artificial Neural Network (ANN)

This project predicts **customer churn** using an **Artificial Neural Network (ANN)** and provides an **interactive web interface built with Streamlit**.
Users can input customer details and instantly get a churn prediction.

🔗 **Live App**:
👉 [https://churnmodellingusingann-jxyqbzwvxtc9ndrnwtqbo9.streamlit.app/](https://churnmodellingusingann-jxyqbzwvxtc9ndrnwtqbo9.streamlit.app/)

---

## 🚀 Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave.
In this project:

* An **ANN model** is trained on banking customer data
* The trained model predicts whether a customer will **churn or not**
* A **Streamlit web app** is used for real-time predictions
* Preprocessing objects and trained models are saved and reused

---

## 🌟 Key Features

* ANN-based churn prediction
* Interactive **Streamlit UI**
* Real-time predictions
* Data preprocessing (encoding & scaling)
* Saved model and encoders (`.pkl`, `.h5`, `.keras`)
* User-friendly web deployment

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Scikit-learn**
* **TensorFlow / Keras**
* **Streamlit**
* **Jupyter Notebook**

---

## 📂 Project Structure

```
churn_modelling_usingANN/
│
├── BankChurners.csv              # Dataset
├── Churn_Modelling.csv           # Dataset
│
├── app.py                        # Streamlit application
├── experiments.ipynb             # Model training & experiments
├── predictions.ipynb             # Prediction testing
│
├── model.h5                      # Trained ANN model
├── model.keras                   # Keras model format
│
├── scaler.pkl                    # StandardScaler
├── ohe_geo.pkl                   # One-Hot Encoder (Geography)
├── label_encoder_gender.pkl      # Label Encoder (Gender)
│
├── requirements.txt              # Dependencies
├── req.txt                       # Alternate requirements file
└── .devcontainer/                # Dev container setup
```

---

## 📦 Installation (Local Setup)

Clone the repository:

```bash
git clone https://github.com/your-username/churn_modelling_usingANN.git
```

Move into the project directory:

```bash
cd churn_modelling_usingANN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Streamlit App Locally

```bash
streamlit run app.py
```

---

## 📊 Input Features

The model uses the following inputs:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

---

## 🎯 Output

* **0 → Customer will NOT churn**
* **1 → Customer WILL churn**

The result is displayed instantly on the Streamlit interface.

---

## 🌐 Live Deployment

The application is deployed using **Streamlit Cloud**.

🔗 **Live App Link**:
[https://churnmodellingusingann-jxyqbzwvxtc9ndrnwtqbo9.streamlit.app/](https://churnmodellingusingann-jxyqbzwvxtc9ndrnwtqbo9.streamlit.app/)

---

## 🔮 Future Enhancements

* Model performance comparison with ML algorithms
* Hyperparameter tuning
* Explainable AI (SHAP / LIME)
* Improved UI/UX
* Dataset expansion

---

## 👩‍💻 Author

**Jahnavi Singh**
B.Tech Student | Machine Learning & AI Enthusiast

---

Just say the word 🚀
