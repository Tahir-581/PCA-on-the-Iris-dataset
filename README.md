# PCA on Iris Dataset

## Overview
This project demonstrates **Principal Component Analysis (PCA)** on the **Iris dataset** using Python. PCA is applied to reduce the dimensionality of the dataset while preserving variance.

## Dataset
The **Iris dataset** consists of 150 samples across 3 species: Setosa, Versicolor, and Virginica. It has 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Features
- **Data Preprocessing:** Load and structure the dataset using Pandas.
- **PCA Transformation:** Reduce dimensionality to 2 principal components.
- **Visualization:** Scatter plot of principal components with color-coded target labels.
- **Explained Variance:** Displays how much variance each principal component retains.

## Installation
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
Run the script to perform PCA and visualize the results:
```bash
python pca_iris.py
```

## Results
- A **scatter plot** showing the transformed data in 2D space.
- The **explained variance ratio** for each principal component.

## Example Output
```
Explained Variance Ratio by Principal Components:
Principal Component 1: 0.92
Principal Component 2: 0.05
```

## License
This project is open-source under the MIT License.

