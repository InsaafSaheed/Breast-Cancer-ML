# Breast Cancer Diagnosis

This repository contains code for a machine learning model to diagnose breast cancer based on various features. The model predicts whether a breast tissue diagnosis is malignant or benign using the provided dataset.

## Dataset

The dataset used for this project contains the following columns:

- `id`: ID number
- `diagnosis`: The diagnosis of breast tissues (M = malignant, B = benign)
- `radius_mean`: Mean of distances from center to points on the perimeter
- `texture_mean`: Standard deviation of gray-scale values
- `perimeter_mean`: Mean size of the core tumor
- `area_mean`: Mean of local variation in radius lengths
- `smoothness_mean`: Mean smoothness of the contour
- `compactness_mean`: Mean of perimeter^2 / area - 1.0
- `concavity_mean`: Mean severity of concave portions of the contour
- `concave points_mean`: Mean number of concave portions of the contour

## Setup and Dependencies

To run the code in this repository, you need to have the following dependencies installed:

- Python 3
- pandas
- scikit-learn

You can install the required dependencies using pip:

pip install pandas scikit-learn

