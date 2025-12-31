# Iris Flower Classification Project

A simple machine learning project that predicts the species of iris flowers based on their measurements.

## What This Project Does

This project uses a machine learning model to classify iris flowers into three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

The model uses four measurements:
- Sepal length
- Sepal width
- Petal length
- Petal width

## Requirements

- Python 3.x
- pandas
- scikit-learn
- openpyxl (for reading Excel files)

Install the required packages:
```bash
pip install pandas scikit-learn openpyxl
```

## How to Use

1. Open the `quick_training_on_iris.ipynb` notebook in Jupyter Notebook or JupyterLab
2. Run all cells from top to bottom
3. The model will:
   - Load training data from `iris-train.xlsx`
   - Train a Random Forest classifier
   - Test on data from `iris-test.xlsx`
   - Show accuracy and performance metrics

## Files

- `quick_training_on_iris.ipynb` - Main notebook with the code
- `iris-train.xlsx` - Training data (110 samples)
- `iris-test.xlsx` - Test data (40 samples)
- `iris.xlsx` - Complete dataset

## Results

After running the notebook, you'll see:
- Model accuracy percentage
- Classification report showing precision and recall
- Confusion matrix showing prediction results


