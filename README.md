# Breast Cancer Prediction

Breast Cancer Prediction is a classification task aimed at predicting whether a breast mass is diagnosed as malignant or benign. The dataset used for this prediction consists of features computed from a digitized image of a fine needle aspirate (FNA) of the breast mass. These features describe various characteristics of the cell nuclei present in the image.

## Dataset Information

The dataset contains the following information for each instance:

- **ID Number**: A unique identifier for each sample.
- **Diagnosis**: The target variable indicating the diagnosis, where:
  - 'M' = Malignant (cancerous)
  - 'B' = Benign (non-cancerous)

### Features

For each cell nucleus, ten real-valued features are computed. These features represent quantitative measurements of the cell nuclei characteristics:

1. **Radius**: Mean distance from the center to points on the perimeter of the nucleus.
2. **Texture**: Standard deviation of gray-scale values in the nucleus.
3. **Perimeter**: The perimeter of the nucleus.
4. **Area**: The area of the nucleus.
5. **Smoothness**: Local variation in radius lengths.
6. **Compactness**: 
   \[
   \text{Compactness} = \frac{(\text{Perimeter})^2}{\text{Area}} - 1.0
   \]
7. **Concavity**: Severity of concave portions of the nucleus contour.
8. **Concave Points**: Number of concave portions of the nucleus contour.
9. **Symmetry**: Symmetry of the nucleus.
10. **Fractal Dimension**: Approximates the "coastline" of the nucleus using fractal geometry.

## Project Objective

The main objective of this project is to develop a machine learning model that can predict whether a breast mass is malignant or benign based on the features extracted from the FNA images. By training and evaluating various machine learning models, we aim to develop a robust predictive system that can assist in the early detection and diagnosis of breast cancer.

## Features Overview

1. **Radius**: Measures the size of the cell nucleus.
2. **Texture**: Indicates how varied the gray-scale values are within the nucleus.
3. **Perimeter**: The length around the nucleus boundary.
4. **Area**: The amount of space the nucleus covers.
5. **Smoothness**: Represents how smooth the nucleus boundary is.
6. **Compactness**: Quantifies how compact or spread out the nucleus is.
7. **Concavity**: Refers to the depth of concave areas in the nucleus boundary.
8. **Concave Points**: Counts the number of concave points in the nucleus boundary.
9. **Symmetry**: Describes how symmetrical the nucleus is.
10. **Fractal Dimension**: Measures the complexity of the nucleus boundary.

## Machine Learning Approach

The project uses various machine learning algorithms, such as:

- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine
- XGBoost Classifier

These models are trained on the dataset to classify tumors as malignant or benign, and their performances are evaluated using metrics like **accuracy**, **precision**, **recall**, and **F1-score**.

## Conclusion

By leveraging the features derived from FNA images, we can build predictive models that are highly accurate in classifying breast cancer tumors. Early detection and diagnosis are critical, and this machine learning-based approach can serve as a tool to aid medical professionals in identifying cancerous masses.
