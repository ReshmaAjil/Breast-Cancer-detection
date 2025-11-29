# Breast-Cancer-detection
Breast cancer detection and analysis project focused on early diagnosis, research, and awareness.
Copy code
# Breast Cancer Detection using Logistic Regression

This project uses the Breast Cancer Wisconsin dataset from `sklearn` to build a Logistic Regression model for classifying tumors as **benign** or **malignant**. The project includes data loading, preprocessing, model training, evaluation, and visualization.

## 📌 Dataset
The dataset is loaded from `sklearn.datasets.load_breast_cancer()` and contains:
- **569 samples**
- **30 features**
- **Target classes:**  
  - 0 = Malignant  
  - 1 = Benign  

## 🧠 Model Used
- **Logistic Regression**  
Selected for its simplicity, speed, and effectiveness in binary classification problems.

## 🚀 Features of This Project
- Loads and displays feature names and target labels
- Converts dataset into a Pandas DataFrame
- Splits data into training and testing sets
- Trains a Logistic Regression model
- Generates:
  - Accuracy Score  
  - Confusion Matrix  
  - Classification Report  
- Visualizes the confusion matrix using Seaborn heatmap
