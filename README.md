# 🍷 Wine Quality Prediction using Machine Learning

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=250&section=header&text=Wine%20Quality%20Prediction&fontSize=35&fontColor=ffffff&animation=fadeIn&fontAlignY=40" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-orange" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

# 📖 Project Overview

This project develops a **Wine Quality Prediction System using Machine Learning** to predict the quality of wine based on its chemical properties.

The model analyzes different physicochemical characteristics of wine such as acidity, sugar content, pH value, alcohol percentage, and other features to estimate wine quality.

Machine Learning techniques are used to learn patterns from historical wine data and predict the quality score of new wine samples.

This project demonstrates the complete Machine Learning workflow including:

- Data Loading
- Exploratory Data Analysis
- Data Preprocessing
- Model Training
- Model Evaluation
- Quality Prediction

---

# 🎯 Project Objectives

The objectives of this project are:

* Analyze wine quality datasets.
* Understand factors affecting wine quality.
* Perform data preprocessing.
* Build a Machine Learning prediction model.
* Predict wine quality based on input features.
* Apply Machine Learning techniques to real-world problems.

---

# 📂 Dataset Information

**Dataset:** Wine Quality Dataset

The dataset contains chemical properties of wine samples along with their quality ratings.

### Features:

| Feature | Description |
|---------|-------------|
| Fixed Acidity | Amount of fixed acids present |
| Volatile Acidity | Amount of volatile acids |
| Citric Acid | Citric acid content |
| Residual Sugar | Remaining sugar content |
| Chlorides | Salt concentration |
| Free Sulfur Dioxide | Free SO₂ level |
| Total Sulfur Dioxide | Total SO₂ level |
| Density | Density of wine |
| pH | Acidity level |
| Sulphates | Sulphate content |
| Alcohol | Alcohol percentage |
| Quality | Wine quality score |

---

# ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Machine Learning Algorithms
* Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Data Collection

The wine quality dataset was loaded and prepared for analysis.

---

## 2. Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Dataset structure
* Feature information
* Missing values
* Statistical properties
* Feature relationships

---

## 3. Data Preprocessing

Performed preprocessing steps:

* Checked missing values.
* Separated input features and target variable.
* Prepared data for model training.

---

## 4. Feature Selection

Input features:

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


Target:

- Wine Quality

---

# ✂️ Train-Test Split

The dataset was divided into training and testing datasets.

| Dataset | Percentage |
|---------|------------|
| Training Data | 80% |
| Testing Data | 20% |

---

# 🤖 Machine Learning Model

The Machine Learning model learns the relationship between wine properties and quality score.

The trained model predicts the quality of unseen wine samples.

---

# 🚀 Model Training

Example:

```python
model.fit(X_train,Y_train)

The model learns patterns from training data and builds a prediction system.

📊 Model Evaluation

The model performance is evaluated using suitable regression metrics:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
🍷 Wine Quality Prediction

The trained model predicts wine quality using new input values.

Example:

prediction = model.predict(input_data_reshape)

print("Wine Quality:", prediction)
Output:
Wine Quality: [7]
📈 Results

The Machine Learning model successfully predicts wine quality based on chemical properties of wine.

The project demonstrates how Machine Learning can help analyze and predict quality scores in the food and beverage industry.

📁 Project Structure
Wine-Quality-Prediction/
│
├── Wine_Quality_Prediction.ipynb
├── winequality.csv
├── README.md
├── requirements.txt
└── .gitignore
🚀 Future Improvements
Compare multiple Machine Learning algorithms.
Improve accuracy using hyperparameter tuning.
Add data visualization dashboard.
Deploy the model using Streamlit.
Build a web-based wine quality prediction application.
📚 Key Learnings

Through this project, I gained practical experience in:

Data Analysis
Data Preprocessing
Feature Engineering
Regression Models
Model Evaluation
Machine Learning Deployment
🌱 Learning Journey

This project is part of my learning journey in:

Artificial Intelligence (AI)
Machine Learning (ML)
Data Science
Generative AI
👩‍💻 Author
Mehar-taj

Aspiring Data Scientist | Machine Learning Enthusiast | AI & Generative AI Learner

GitHub:
https://github.com/Mehar-taj

LinkedIn:
https://www.linkedin.com/in/mehar-taj-a654102b6

⭐ If you found this project useful, consider giving it a star and exploring my other Machine Learning projects.
