# AI_ML_Internship-Task-15
# End-to-End Machine Learning Pipeline

## 📌 Objective
To build a complete machine learning pipeline that integrates preprocessing and model training, ensuring a clean, efficient, and deployment-ready workflow.

## Dataset
* Breast Cancer Dataset (sklearn)
* Features: 30
* Target: Binary classification (Malignant / Benign)

## 🛠️ Tools Used
* Python
* Scikit-learn
* NumPy
* Pandas
* Matplotlib
  
## Steps Performed

1. Loaded dataset from sklearn
2. Split into training and testing sets
3. Built pipeline:
   * StandardScaler (scaling)
   * Logistic Regression (model)
4. Trained pipeline
5. Generated predictions
6. Evaluated model using multiple metrics
7. Visualized results (Confusion Matrix, ROC Curve)
8. Saved trained pipeline

## 📊 Evaluation Metrics

| Metric    | Value |
| --------- | ----- |
| Accuracy  | ~97%  |
| Precision | ~97%  |
| Recall    | ~97%  |
| F1 Score  | ~97%  |

## Saved Model
* File: `ml_pipeline_model.pkl`
  
## Key Insights
* Pipeline ensures consistent preprocessing
* Prevents data leakage
* Simplifies workflow
* Makes model deployment-ready
