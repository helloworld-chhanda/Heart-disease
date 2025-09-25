# Heart Disease Prediction

This project predicts the likelihood of heart disease in patients using various machine learning algorithms.

## Dataset

- **Source:** [Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- The dataset contains patient health measurements and a target indicating the presence of heart disease.

## Machine Learning Algorithms Used

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting

## Model Saving and Loading

- Models are saved and loaded using the [`joblib`](https://joblib.readthedocs.io/en/latest/) library for efficient serialization and deserialization.

## Project Overview

1. **Data Preprocessing**: Cleaning and preparing the data for modeling.
2. **Model Training**: Fitting multiple models to the dataset.
3. **Evaluation**: Comparing model performance using metrics such as accuracy, precision, recall, and F1-score.
4. **Prediction**: 
   - The trained Random Forest model was used for final testing and prediction on new data.

## How to Run

1. Clone the repository.
2. Install requirements (see `requirements.txt`).
3. Download the dataset from Kaggle and place it in the project directory.
4. Run the Jupyter Notebook to see results and visualizations.

## Results

Performance comparison of all algorithms is included in the notebook. 
The Random Forest model was used to test new/unseen data for heart disease prediction.

---

**Note:** This project is for educational purposes and should not be used for medical diagnosis.
