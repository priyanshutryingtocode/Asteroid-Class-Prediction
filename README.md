# ☄️ Asteroid Class Prediction using Machine Learning

An end-to-end machine learning project that predicts the class of an asteroid based on its physical and orbital characteristics. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and prediction using a real-world astronomical dataset.

---

## 📖 Project Overview

Asteroids are classified into different types based on their composition, reflectivity, and orbital properties. Accurately identifying these classes helps astronomers understand the formation and evolution of our Solar System.

This project applies supervised machine learning techniques to classify asteroids using features extracted from a publicly available dataset.

---

## 🚀 Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering and selection
* Machine learning model training
* Model evaluation using multiple performance metrics
* Prediction of asteroid classes
* End-to-end implementation in Python

---

## 📂 Dataset

The dataset used in this project is publicly available on Kaggle.

**Source:**
https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset

The dataset contains various physical and orbital characteristics of asteroids, including features such as:

* Diameter
* Absolute Magnitude
* Albedo
* Orbital Parameters
* Spectral Information
* Other astronomical measurements

The target variable is the **asteroid class**.

---

## 🛠️ Tech Stack

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Repository Structure

```text
Asteroid-Class-Prediction/
│
├── MAIN.ipynb              # End-to-end training pipeline
├── preprocess.ipynb        # Data preprocessing
├── featureanalysis.ipynb   # Exploratory data analysis
├── prediction.ipynb        # Prediction on new data
├── testdatagen.ipynb       # Test dataset generation
├── Test Dataset/
├── requirements.txt
└── README.md
```

---

## ⚙️ Machine Learning Workflow

The project follows a standard supervised machine learning pipeline:

1. Load the dataset
2. Clean and preprocess the data
3. Handle missing values
4. Perform exploratory data analysis
5. Encode categorical features (if required)
6. Split the dataset into training and testing sets
7. Train the machine learning model
8. Evaluate model performance
9. Generate predictions

---

## 📊 Model Evaluation

The trained model is evaluated using standard classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help assess how well the model predicts asteroid classes on unseen data.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/priyanshutryingtocode/Asteroid-Class-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Asteroid-Class-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

If you do not have a `requirements.txt` yet, install the primary libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
MAIN.ipynb
```

and run all cells.

---

## 📈 Example Workflow

```text
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Asteroid Class Prediction
```
---

## 🤝 Contributing

Contributions are welcome!

If you have suggestions or improvements:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is intended for educational and research purposes.

---

## 👤 Author

**Priyanshu Srivastava**

GitHub: https://github.com/priyanshutryingtocode

