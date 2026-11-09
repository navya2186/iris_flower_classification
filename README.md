# 🌸 Iris Flower Classification using Machine Learning

## Project Overview

This project uses Machine Learning to classify Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The model predicts the flower species using four measurements.

## Dataset

The Iris dataset contains:
- 150 flower samples
- 4 input features
- 3 target classes

### Input Features
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

## Machine Learning Algorithms

Two classification algorithms were explored:

- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

KNN was further improved using feature scaling and 5-fold cross-validation.

## Model Performance

- Best K value: 3
- Cross-validation accuracy: 96.67%
- Final KNN test accuracy: 93.33%

## Confusion Matrix

The confusion matrix helps evaluate how accurately the model classifies each flower species.

## Interactive Iris Flower Predictor

An interactive prediction interface was developed using Python and Google Colab.

Users can enter four flower measurements and receive a predicted species along with a short description.

The application also includes input validation.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- IPyWidgets
- Joblib

## Project Files

- `Iris_Flower_Classification.ipynb` – Complete project notebook
- `confusion_matrix.png` – Model evaluation visualization
- `iris_knn_model.pkl` – Saved trained model

## Future Improvements

- Build a web-based prediction application.
- Improve model performance through further experimentation.
- Add more visualizations and model comparisons.

## Conclusion

This project demonstrates how Machine Learning can be used for flower classification. It covers dataset exploration, preprocessing, model training, evaluation, model saving, and interactive prediction.
