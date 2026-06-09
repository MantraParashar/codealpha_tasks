# Iris Flower Classification

## Project Overview

This project uses Data Science to classify Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The classification is based on flower measurements such as:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The model is trained using the Random Forest Classifier from Scikit-learn.

---

## Dataset

The Iris dataset is one of the most popular datasets in Machine Learning.

Dataset Source:
https://www.kaggle.com/datasets/saurabh00007/iriscsv

Number of Records: 150

Number of Features: 4

Target Classes:
1. Setosa
2. Versicolor
3. Virginica

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Project Workflow

### 1. Import Libraries

Required Python libraries were imported for data analysis, visualization, and machine learning.

### 2. Load Dataset

The Iris dataset was loaded using Pandas.

### 3. Data Exploration

The following checks were performed:

- Dataset shape
- Data types
- Missing values
- Class distribution

### 4. Data Preprocessing

- Features and target variables were separated.
- Species labels were encoded using LabelEncoder.

### 5. Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

### 6. Model Training

Random Forest Classifier was used to train the model.

### 7. Prediction

The trained model predicted flower species on test data.

### 8. Evaluation

Model performance was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Model Used

Random Forest Classifier

Advantages:

- High Accuracy
- Handles Classification Problems Efficiently
- Less Overfitting Compared to Single Decision Trees

---

## Results

Accuracy Achieved:

Approximately 97% to 100%

The model successfully classified Iris flower species with high accuracy.

---

## Output Screenshots

### Confusion Matrix

Add screenshot here:

<img width="501" height="393" alt="confusion_matrix" src="https://github.com/user-attachments/assets/abd25818-a20a-490a-992f-21c26439ce1d" />


---

## How to Run

1. Clone the repository

git clone https://github.com/YourUsername/CodeAlpha_Iris_Classification.git

2. Install dependencies

pip install -r requirements.txt

3. Run the notebook

Open Iris_Classification.ipynb in Google Colab or Jupyter Notebook.

---

## Project Structure

CodeAlpha_Iris_Classification/

├── Iris_Classification.ipynb

├── iris.csv

├── README.md

├── requirements.txt

└── screenshots/

    <img width="501" height="393" alt="confusion_matrix" src="https://github.com/user-attachments/assets/fc6294b6-e71a-4111-b79a-8545cc402ea4" />

---

## Learning Outcomes

Through this project, I learned:

- Data Preprocessing
- Classification Algorithms
- Random Forest Classifier
- Model Evaluation
- Confusion Matrix Analysis
- Machine Learning Workflow

---

## Author

Name: Your Name

Internship: CodeAlpha Machine Learning Internship
