# ANN Model Training & Prediction (with TensorBoard)

## 📌 Project Overview  
This project demonstrates how to build and train an **Artificial Neural Network (ANN)** model for classification using the **Churn_Modelling.csv** dataset.  

It includes:  
- Data preprocessing (encoding & scaling).  
- ANN model training using TensorFlow/Keras.  
- Saving trained model & preprocessing objects (`.h5` and `.pkl` files).  
- Predictions on test data.  
- Training visualization with **TensorBoard**.  

---

## 🛠️ Tech Stack  
- **Python 3**  
- **TensorFlow / Keras**  
- **Pandas, NumPy, Scikit-Learn**  
- **TensorBoard** (for visualization)  
- **Pickle** (for saving encoders/scaler)  

---

## 📂 Project Structure  
├── salaryregression.ipynb # ANN training & prediction notebook
├── model.h5 # Trained ANN model
├── label_encoder_gender.pkl # Label encoder for Gender
├── onehot_encoder_geography.pkl # One-hot encoder for Geography
├── scaler.pkl # Standard scaler for features
├── Churn_Modelling.csv # Dataset
└── README.md # Project documentation




---

## 🚀 How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/ItsMeVenom-Dev/ANN_Regression.git
cd ANN_Regression
```

### 2️⃣ Install Dependencies
pip install -r requirements.txt


### 3️⃣ Run Jupyter Notebook
jupyter notebook salaryregression.ipynb


This project is licensed under the Apache License 2.0
