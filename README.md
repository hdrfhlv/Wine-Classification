# 🍷 Wine Classification Using K-Nearest Neighbors (KNN)

## 📌 About the Project

This project implements a Machine Learning classification model to predict wine classes based on their chemical properties using the **K-Nearest Neighbors (KNN)** algorithm.

The model uses the built-in Wine Dataset from Scikit-learn, which contains chemical measurements of wine samples divided into three different classes.

## 🎯 Project Objectives

- Understand the fundamentals of Machine Learning classification.
- Explore and analyze the Wine Dataset.
- Implement the K-Nearest Neighbors algorithm.
- Apply feature scaling using StandardScaler.
- Evaluate model performance using accuracy.

## 📊 Dataset Information

The dataset is provided by `sklearn.datasets.load_wine()`.

| Information | Description |
|---|---|
| Dataset | Wine Dataset |
| Total Samples | 178 |
| Total Features | 13 |
| Target Classes | 3 |
| Problem Type | Multiclass Classification |

### Features

Some of the chemical properties used:
- Alcohol
- Malic Acid
- Ash
- Magnesium
- Total Phenols
- Flavanoids
- Color Intensity
- Proline

## 🛠️ Technologies & Libraries

- Python
- Scikit-learn
- Pandas

## ⚙️ Machine Learning Workflow

1. Load the Wine Dataset.
2. Separate features (X) and target (y).
3. Split the dataset into training and testing sets.
4. Apply StandardScaler for feature scaling.
5. Train the KNN classification model.
6. Make predictions.
7. Evaluate model performance.

## 🤖 Algorithm

**K-Nearest Neighbors (KNN)**

KNN is a supervised Machine Learning algorithm that classifies new data based on the majority class of its nearest neighbors.

Model configuration:
- Algorithm: K-Nearest Neighbors
- Number of Neighbors (K): 5
- Feature Scaling: StandardScaler
- Random State: 45

## 📈 Model Performance

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 0.9859154929577465 |
| Accuracy (%) | **98.59%** |

The model achieved an accuracy of approximately **98.59%** on the test dataset.

## 📂 Project Structure

```text
wine-classification/
│
├── wine_classification.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/wine-classification.git
```

2. Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run `wine_classification.ipynb`.

## 📚 What I Learned

Through this project, I learned how to:
- Work with built-in Scikit-learn datasets.
- Prepare data for Machine Learning.
- Understand and implement KNN.
- Apply feature scaling.
- Split datasets into training and testing sets.
- Evaluate classification model accuracy.

## 👨‍💻 Author

**Muhammad Haidar Fahlevi**

Informatics Student | Machine Learning Enthusiast

Interested in Machine Learning, Artificial Intelligence, Data Science, and Data Analysis.
