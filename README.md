# 📊 ANN-Based Churn Classifier

An Artificial Neural Network (ANN) model built to predict customer churn with high accuracy. This project uses TensorFlow and Streamlit to provide an interactive and intuitive web app for churn analysis.

### 🚀 Live App:
👉 [Launch Streamlit App](https://ann-based-churn-classifier-ccjgrvuo5gshdappzhde4qt.streamlit.app/)

---

## 🧠 Overview

Customer churn is when a customer stops doing business with a company. Understanding and predicting churn is vital for businesses in competitive markets. This project builds an ANN to classify whether a customer is likely to churn based on historical data.

---

## 📁 Project Structure

```

ANN-Based-Churn-Classifier/
│
├── app.py                 # Streamlit application
├── churn\_model.h5        # Trained ANN model
├── requirements.txt      # Dependencies for the app
├── data.csv              # Dataset used for training and testing
├── utils.py              # Helper functions (if any)
└── README.md             # Project documentation

````

---

## ⚙️ Features

✅ Pre-trained ANN model  
✅ Real-time prediction of customer churn  
✅ Interactive UI with Streamlit  
✅ Data visualization and user input support  
✅ Clean and responsive design  

---

## 🖥 Demo Screenshots

*(Insert screenshots if needed)*

---

## 📌 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/niksom406/ANN-Based-Churn-Classifier.git
cd ANN-Based-Churn-Classifier
````

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Run the app:

```bash
streamlit run app.py
```

---

## 🧪 Model Details

* Architecture: Fully-connected ANN
* Layers: Input → Hidden (ReLU) → Output (Sigmoid)
* Loss: Binary Crossentropy
* Optimizer: Adam
* Accuracy: \~86% (on test data)

---

## 🧠 Technologies Used

* Python 🐍
* TensorFlow
* Pandas & NumPy
* Scikit-learn
* Streamlit

---

## 🗂 Dataset

The dataset used includes customer demographics and account information such as:

* Credit Score
* Geography
* Age
* Tenure
* Balance
* Number of Products
* IsActiveMember
* Estimated Salary
* Exited (Churn Label)

---

## 📌 Author

**Nikita Somani**
[GitHub](https://github.com/niksom406)

---

## 💡 Future Improvements

* Allow uploading custom datasets
* Model retraining from UI
* Improved interpretability (e.g., SHAP values)
* Deploy with Docker for scalability

### 🔗 Useful Links

* [Streamlit Documentation](https://docs.streamlit.io/)
* [TensorFlow Documentation](https://www.tensorflow.org/)
