# Iris ML Project 🌸

A beginner-friendly machine learning project using the classic Iris dataset and a K-Nearest Neighbors (KNN) classifier.

## What this project does

- Loads the Iris dataset from scikit-learn
- Explores the data with pandas
- Splits into train/test sets
- Trains a KNN classifier
- Evaluates with accuracy and a confusion matrix
- Predicts the class of a new flower sample

## How to run

```bash
git clone https://github.com/KanakAcharya/iris_ml_project.git
cd iris_ml_project
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python iris_classifier.py
```

## Files

- `iris_classifier.py` – main ML script
- `confusion matrix plot.png` – confusion matrix visualization
- `requirements.txt` – Python dependencies

## Dataset

The Iris dataset contains 150 samples of iris flowers across 3 species:
- Setosa
- Versicolor
- Virginica

Each sample has 4 measurements: sepal length, sepal width, petal length, petal width.

## Model Performance

KNN classifier with k=3 achieves high accuracy on the test set.
