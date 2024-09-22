# RBF (Radial Basis Function) for Classification

This repository contains a Jupyter notebook that implements a Radial Basis Function (RBF) classifier for classification tasks using various RBF types. The project demonstrates data visualization, data preprocessing, model training, and evaluation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Implementation Details](#implementation-details)
- [Results](#results)

## Installation

Ensure you have the following libraries installed:

```bash
pip install pandas numpy scipy scikit-learn matplotlib
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/rbf-classification.git
   cd rbf-classification
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook RBF\ (Radial\ Basis\ Function)\ for\ Classification.ipynb
   ```

3. Follow the instructions within the notebook to load your data and train the RBF classifier.

## Data Description

The dataset consists of two files:
- `X.dat`: Features for classification.
- `Y.dat`: Corresponding labels for the features.

The notebook samples 100 records from the dataset for analysis.

## Implementation Details

### Libraries Used
- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical computations.
- `scipy`: Scientific computations.
- `matplotlib`: Data visualization.
- `sklearn`: Machine learning tools.

### Features
- Data loading and sampling
- Visualization of data distribution in 3D and 2D
- Implementation of the K-means clustering algorithm
- RBF class definition with multiple RBF types:
  - Gaussian
  - Inverse Multiquadric
  - Multiquadric
  - Linear Spline
  - Cubic Spline
- Model training and evaluation using K-fold cross-validation

### Training and Evaluation
- The model is trained using 70% of the data and tested on 30%.
- K-fold cross-validation is used to validate the model's performance.
- The accuracy and error rates are reported for training, validation, and test sets.

## Results

The results include:
- Classification reports for different RBF types.
- Visualizations of training, validation, and test error rates.
- Accuracy metrics for each RBF type based on different training data sizes.
