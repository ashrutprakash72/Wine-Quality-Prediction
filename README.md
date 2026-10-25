# 🍷 Wine Quality Prediction using Machine Learning

## 📖 Overview

This project uses Machine Learning techniques to predict the quality of wine based on its physicochemical properties. The dataset contains various wine attributes such as acidity, sugar, alcohol content, pH, and sulphates, which are analyzed to build a predictive model.

The project includes:

- Data Exploration and Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Data Preprocessing
- Model Training
- Model Evaluation
- Wine Quality Prediction

---

## 📊 Dataset Features

The dataset contains the following features:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis

The project performs:

### Quality Distribution Analysis
- Visualization of wine quality ratings.
- Identification of dataset balance.

### Feature Analysis
- Alcohol vs Quality
- Volatile Acidity vs Quality
- Correlation between features

### Correlation Heatmap
A heatmap is generated to understand relationships among features and their impact on wine quality.

---

## ⚙️ Data Preprocessing

Steps performed:

1. Handling missing values
2. Feature selection
3. Label transformation
4. Train-Test split
5. Data normalization (if required)

---

## 🤖 Machine Learning Model

### Random Forest Classifier

The model used for prediction is:

```python
RandomForestClassifier()
```

### Training Process

```python
X_train, X_test, Y_train, Y_test = train_test_split(
    X, Y, test_size=0.2, random_state=2
)
```

---

## 📋 Model Evaluation

Performance is evaluated using:

- Accuracy Score
- Predictions on Test Data

Example Result:

```text
Accuracy Score: 87%
```

*(Accuracy may vary depending on random state and preprocessing.)*

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/wine-quality-prediction.git
cd wine-quality-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Wine_Quality_Prediction.ipynb
```

---

## 📂 Project Structure

```text
wine-quality-prediction/
│
├── Wine_Quality_Prediction.ipynb
├── winequality.csv
├── requirements.txt
├── README.md
└── images/
```

---

## 🎯 Future Improvements

- Hyperparameter Tuning
- Multiple Model Comparison
- Deploy using Flask/Django
- Create Web Interface
- Model Export using Pickle

---

## 👨‍💻 Author

Ashrut Prakash

Student | Python Developer | Machine Learning Enthusiast

GitHub: https://github.com/ashrutprakash72
---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

