# Self-Organizing Map with ANN

A hybrid model combining Self-Organizing Maps (SOM) with Artificial Neural Networks for fraud detection in credit card applications.

## Overview

This project implements a two-stage machine learning pipeline:
1. **Unsupervised Learning (SOM)** — Identifies patterns and anomalies in credit card applications
2. **Supervised Learning (ANN)** — Predicts probability of fraudulent behavior

## Use Case

Detecting potentially fraudulent credit card applications by:
- Using SOM to identify outliers and suspicious patterns
- Training ANN on identified patterns to predict fraud probability

## Features

- 🧠 **Self-Organizing Map** — Unsupervised clustering of application data
- 🔮 **Neural Network** — Supervised classification of fraud risk
- 📊 **Visualization** — SOM grid visualization of clusters
- 🎯 **Hybrid Approach** — Combines strengths of both methods

## Requirements

- Python 3.x
- NumPy
- pandas
- Keras/TensorFlow
- minisom

## Dataset

Bank credit card application dataset with customer attributes.

## Usage

```bash
jupyter notebook SOM_ANN_Hybrid.ipynb
```

## How It Works

1. **SOM Phase:** Maps high-dimensional data to 2D grid, identifies outliers
2. **Labeling:** Outliers flagged as potential fraud
3. **ANN Phase:** Trained on labeled data to predict fraud probability
4. **Prediction:** Outputs fraud probability for new applications

## Results

The hybrid model improves fraud detection by leveraging unsupervised pattern recognition before supervised classification.

## License

MIT
