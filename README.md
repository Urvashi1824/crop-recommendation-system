# 🌱 Crop Recommendation System

A Machine Learning-based project that predicts suitable crops based on soil nutrients and environmental conditions.

## 📌 Project Overview

This project uses classification algorithms to recommend suitable crops based on seven input features: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.

## 🎯 Objectives

- Analyze agricultural soil and environmental data.
- Apply Machine Learning classification algorithms.
- Compare model performance.
- Select the best-performing model for crop prediction.

## 📊 Dataset

- **Dataset:** Crop Recommendation Dataset
- **Records:** 2,200
- **Input Features:** 7
- **Crop Categories:** 22
- **Target Variable:** label

**Dataset Source:** [Kaggle – Crop Recommendation Dataset](https://www.kaggle.com/datasets/madhuraatmarambhagat/crop-recommendation-dataset)

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 🤖 Machine Learning Algorithms

1. Decision Tree Classifier
2. Random Forest Classifier
3. Support Vector Machine (SVM)

## 📈 Model Performance

| Algorithm | Accuracy |
|---|---:|
| Decision Tree | 97.95% |
| Random Forest | 99.55% |
| SVM | 98.41% |

Random Forest achieved the highest accuracy of **99.55%** on the test dataset and was selected as the best-performing model.

## 🔍 Feature Importance

Rainfall and Humidity were the most influential features in the trained Random Forest model.

## 📁 Project Files

- `Crop_Recommendation.ipynb` – Complete project implementation and analysis.
- `crop_recommendation_model.pkl` – Trained Random Forest model.

## ▶️ How to Use

1. Download the project notebook.
2. Open it using Google Colab.
3. Upload the Crop Recommendation dataset.
4. Run the notebook cells to reproduce the analysis and training.

To load the saved model:

```python
import joblib

model = joblib.load('crop_recommendation_model.pkl')
```

## ⚠️ Note

The reported accuracy is based on the selected train-test split. Predictions are educational and experimental, and should not be treated as guaranteed agricultural advice.

## 👩‍💻 Project Information

Developed as a Machine Learning project using Python and Scikit-learn.
