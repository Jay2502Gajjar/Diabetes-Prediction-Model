# Diabetes Prediction using Machine Learning

## 📌 Overview
This project is a machine learning–based system that predicts whether a person is diabetic or non-diabetic using medical diagnostic data.  
The model is trained using the **PIMA Indians Diabetes Dataset** and implements a **Support Vector Machine (SVM)** classifier.

The project focuses on proper data preprocessing, feature scaling, and building a reliable prediction system.

---

## 🩺 Dataset
- **PIMA Indians Diabetes Dataset**
- Features used:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- Target:
  - `0` → Non-Diabetic
  - `1` → Diabetic

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Model Used
- **Support Vector Machine (SVM)**
- Kernel: `linear`
- Feature scaling done using **StandardScaler**

---

## 🔄 Project Workflow
1. Load and analyze the dataset
2. Separate features and target labels
3. Standardize feature values
4. Split data into training and testing sets
5. Train the SVM classifier
6. Evaluate model accuracy
7. Build a predictive system for new input data

---

## 📊 Results
The model achieves good accuracy on both training and testing datasets and can successfully predict diabetes based on input health parameters.

---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-ml.git
