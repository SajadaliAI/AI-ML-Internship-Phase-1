# ❤️ Heart Disease Prediction using Machine Learning

This project applies **machine learning and data analysis techniques** to predict the presence of heart disease using clinical patient data.

The project was developed as part of the **DevelopersHub AI/ML Internship — Phase 1**.

---

## 🎯 Project Objective

The objective is to analyze clinical features and build a machine learning classification model that can estimate whether a patient is likely to have heart disease.

This project is intended for **educational and machine learning demonstration purposes** and is not a medical diagnostic system.

---

## 📊 Dataset

The project uses a heart disease dataset containing clinical features related to patients.

The dataset is stored inside:

```text
dataset/
```

Common clinical features include information such as:

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol
* Fasting blood sugar
* Resting ECG
* Maximum heart rate
* Exercise-induced angina
* ST depression
* Slope
* Number of major vessels
* Thal
* Target

The target variable represents the presence or absence of heart disease.

---

## 🔄 Project Workflow

```text
Heart Disease Dataset
        ↓
Data Loading
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Analysis
        ↓
Machine Learning Classification
        ↓
Model Evaluation
        ↓
Prediction
```

---

## 🧹 Data Preprocessing

The notebook performs data preparation before model training.

The preprocessing workflow includes:

* Inspecting the dataset
* Handling data quality issues
* Preparing features
* Preparing the target variable
* Transforming data for machine learning

---

## 📊 Exploratory Data Analysis

Exploratory Data Analysis is performed to understand the dataset and relationships between clinical features.

The analysis includes:

* Feature distributions
* Data visualization
* Correlation analysis
* Relationship between features and target
* Identification of important patterns

---

## 🤖 Machine Learning

A machine learning classification approach is used to predict heart disease from the available clinical features.

The complete implementation can be found in:

```text
heart_disease_prediction.ipynb
```

---

## 📈 Model Evaluation

The notebook evaluates the model using appropriate classification metrics and visualizations.

The evaluation helps determine how effectively the model distinguishes between patients with and without heart disease.

---

## 📂 Project Structure

```text
Task-2-Heart-Disease-Prediction/
│
├── dataset/
│
├── heart_disease_prediction.ipynb
│
└── README.md
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Machine Learning

---

## 📦 Installation

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## ▶️ Run the Project

Open the notebook:

```bash
jupyter notebook heart_disease_prediction.ipynb
```

Run the notebook cells sequentially to reproduce the data analysis, model training, and evaluation.

---

## 📚 Skills Demonstrated

* Python programming
* Data preprocessing
* Exploratory Data Analysis
* Data visualization
* Feature analysis
* Classification
* Machine learning
* Model evaluation
* Working with healthcare datasets

---

## ⚠️ Disclaimer

This project is intended for **educational and machine learning demonstration purposes only**. It should not be used as a substitute for professional medical diagnosis or clinical decision-making.
