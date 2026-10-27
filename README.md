# Iris Classifier

A scikit-learn classifier trained on the Iris dataset, built as part of my ML learning path.

## Dataset
- 150 samples, 4 features (sepal length/width, petal length/width)
- 3 classes: setosa, versicolor, virginica
- 80/20 train/test split (random_state=42 for reproducibility)

## Model
LogisticRegression (max_iter=200)

## Results
- Accuracy: 100% (1.0) on the 30-sample test set
- Note: Iris is a small, linearly separable dataset. 100% here doesn't mean the model is perfect — it means this dataset is easy. My next project (MNIST with a NumPy neural net from scratch) is the real benchmark.

## How to run
Open `iris.ipynb` in Google Colab and run all cells.

## What I learned
- The sklearn workflow: `fit` → `predict` → `score`
- Why train/test split matters — testing on unseen data
- Why accuracy alone can be misleading on imbalanced data
