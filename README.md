# Iris Dataset Classification Using SVM

This project focuses on visualizing the distribution of petal and sepal dimensions from the Iris dataset and classifying the species using a Support Vector Machine (SVM) classifier.

## Project Overview

The Iris dataset is one of the most well-known datasets for classification tasks. In this project:
1. The distribution of **Petal Length**, **Petal Width**, **Sepal Length**, and **Sepal Width** is visualized.
2. A Support Vector Machine (SVM) classifier is implemented to classify the three Iris species: `Iris-setosa`, `Iris-versicolor`, and `Iris-virginica`.
3. The decision boundary of the SVM model is plotted for visual interpretation.

---

## Dataset

The Iris dataset contains 150 rows and 5 columns:
- **SepalLengthCm**: Sepal length in centimeters.
- **SepalWidthCm**: Sepal width in centimeters.
- **PetalLengthCm**: Petal length in centimeters.
- **PetalWidthCm**: Petal width in centimeters.
- **Species**: Species name (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`).

---

## Steps in the Project

### 1. Visualizing Distributions

- Histograms are created for `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, and `PetalWidthCm` to observe the distribution of each feature.
- ![image](https://github.com/user-attachments/assets/797af768-19d5-4760-a7f0-8d6296bd27dd)
- ![image](https://github.com/user-attachments/assets/b5d59924-1f4d-4954-8e07-1917ed04f4d4)



### 2. Support Vector Machine Classification

- An SVM classifier is trained on the `PetalLengthCm` and `PetalWidthCm` features to classify the Iris species.
- The decision boundary is plotted for visual interpretation of the classifier's performance.
![image](https://github.com/user-attachments/assets/c0223016-1525-410c-b233-7946626f1629)


### 3. Evaluation

- The accuracy of the classifier is calculated using the test set.
- The decision boundary is overlaid on the scatterplot of the test data to show the model's performance.
![image](https://github.com/user-attachments/assets/eaa298e7-abd3-481b-a199-49b3add99c44)

---

## Technologies Used

- **Python**: Programming language
- **Jupyter Notebook**: For interactive coding
- **NumPy**: Numerical operations
- **Pandas**: Data manipulation
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning framework

---

## Visualization

### Distribution Histograms

Histograms of petal and sepal dimensions are created to explore the distribution of the features.

### SVM Decision Boundary

The SVM decision boundary is visualized to illustrate the classifier's separability among different species.

---

## Installation

## Clone the repository:
## Results
Classifier Accuracy: The SVM classifier achieved an accuracy of XX% on the test set.

Decision Boundary: The decision boundary demonstrates the model's ability to separate the three species based on petal dimensions.

## Example Visualizations
1. Feature Distributions
2. SVM Decision Boundary
