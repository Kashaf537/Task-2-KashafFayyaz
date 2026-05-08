# 🌸 Data Classification using Machine Learning

A beginner-friendly **Machine Learning Classification Project** built using **Python**, **Scikit-learn**, **Pandas**, and **Matplotlib**.

This project uses the famous **Iris Dataset** to classify flower species using the **Logistic Regression** algorithm.  
It also includes data visualization, model training, evaluation metrics, and prediction of new flower samples.

---

# 📌 Project Overview

The goal of this project is to build a machine learning model capable of predicting the species of an iris flower based on its physical measurements.

The project demonstrates:
- 📊 Data analysis
- 📈 Data visualization
- 🤖 Machine learning classification
- 📉 Model evaluation
- 🌸 Predicting flower species

This is an excellent beginner project for students learning:
- Machine Learning
- Data Science
- Classification algorithms
- Python for AI

---

# 🌸 About the Iris Dataset

The Iris dataset contains measurements of iris flowers from 3 different species:

1. **Setosa**
2. **Versicolor**
3. **Virginica**

Each flower contains 4 features:

| Feature | Description |
|----------|-------------|
| Sepal Length | Length of sepal |
| Sepal Width | Width of sepal |
| Petal Length | Length of petal |
| Petal Width | Width of petal |

Dataset Details:
- Total Samples: **150**
- Features: **4**
- Classes: **3**

---

# ✨ Main Features

## 📊 Dataset Loading & Understanding
The project:
- Loads the Iris dataset
- Converts it into a Pandas DataFrame
- Displays:
  - Dataset shape
  - First few rows
  - Feature names
  - Target classes
  - Class distribution

---

## 📈 Data Visualization

The project creates **3 different graphs** to better understand the data.

### 1️⃣ Box Plot
Shows feature distributions for each flower species.

Purpose:
- Compare measurements between species
- Detect variation in data

---

### 2️⃣ Scatter Plot
Plots:
- Petal Length vs Petal Width

Purpose:
- Visualize how species are separated
- Understand classification boundaries

---

### 3️⃣ Correlation Heatmap
Displays correlation between features.

Purpose:
- Identify strongly related features
- Understand feature relationships

---

## 🤖 Machine Learning Model

The project uses:

### Logistic Regression
A supervised machine learning classification algorithm used to predict flower species.

The model:
- Learns patterns from training data
- Predicts species for unseen flowers

---

## 🔀 Train-Test Splitting

The dataset is divided into:
- **80% Training Data**
- **20% Testing Data**

This helps evaluate how well the model performs on new data.

---

## 📉 Model Evaluation

The project evaluates model performance using:

| Metric | Purpose |
|--------|---------|
| Accuracy Score | Overall prediction accuracy |
| Classification Report | Precision, recall, F1-score |
| Confusion Matrix | Correct vs incorrect predictions |

---

## 🌸 Predicting a New Flower

The project tests the trained model using a new flower sample.

🛠️ Technologies Used
Technology	Purpose
Python	Main programming language
NumPy	Numerical operations
Pandas	Data handling
Matplotlib	Data visualization
Scikit-learn	Machine learning tools
📂 Project Structure
Data-Classification-Project/
│
├── classification.py      # Main project file
├── README.md              # Project documentation
└── requirements.txt       # Required libraries
⚙️ How the Project Works
Step 1: Load Dataset

The Iris dataset is loaded using Scikit-learn.

Step 2: Analyze Data

The program displays:

Shape of dataset
Sample rows
Species distribution

Step 3: Visualize Data

Graphs are generated to understand:

Feature distributions
Species separation
Feature correlations

Step 4: Split Dataset

Data is divided into:

Training set
Testing set

Step 5: Train Model

Logistic Regression is trained using the training dataset.

Step 6: Evaluate Model

The model predicts test data and calculates:

Accuracy
Classification report
Confusion matrix

Step 7: Predict New Sample

The model predicts the species of a completely new flower.

▶️ How to Run the Project

Step 1: Install Python

Download and install Python:

https://www.python.org/downloads/

Step 2: Install Required Libraries

Open terminal or command prompt and run:

pip install numpy pandas matplotlib scikit-learn

Step 3: Save the Python File

Save the code as:

Iris classification.py

Step 4: Run the Project

Run the following command:

python Iris classification.py

📊 Expected Output

The program will:

Display dataset information

Show 3 visual graphs

Train the Logistic Regression model

Display:
Accuracy score
Classification report
Confusion matrix
Predict a new flower species

📈 Example Results
Result	Example
Accuracy	~96% to 100%
Algorithm	Logistic Regression
Classes	3 flower species

🎯 Learning Outcomes

This project helps beginners learn:

Machine Learning basics
Classification algorithms
Logistic Regression
Data preprocessing
Data visualization
Model evaluation
Working with datasets
Python libraries for AI

Example Input:
```python id="2ygt7f"
[5.1, 3.5, 1.4, 0.2]
