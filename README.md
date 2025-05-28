# Bank-Churn-Analysis-
# 🔍 Bank Customer Churn Prediction

This project is a comprehensive end-to-end implementation of a **customer churn prediction system** for the banking sector. It combines **statistical analysis**, **machine learning**, and **Power BI visualizations** to both predict churn and explain the underlying reasons driving customer attrition.

---

## 📊 Project Objectives

- Identify which bank customers are likely to churn.
- Understand key factors contributing to churn using statistical techniques.
- Build predictive models (Logistic Regression, Random Forest, SVM).
- Visualize churn patterns in Power BI to communicate results effectively to stakeholders.

---

## 🧠 Techniques Used

### 🧪 Statistical Analysis
- **Welch’s T-Test**: Identify numerical features with significantly different means between churned and retained customers.
- **Chi-Square Test**: Test dependence between categorical features and churn.
- **Correlation Heatmap**: Explore linear relationships.

### 🤖 Machine Learning
- **Logistic Regression**: Linear model for baseline prediction.
- **Random Forest**: Ensemble model for handling complex interactions.
- **Support Vector Machine (SVM)**: Classifier for high-dimensional spaces.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

### 📊 Power BI Visualization
- Unpivoted churn distribution across demographics (gender, geography, credit card, active membership).
- 100% stacked bar charts and clustered visuals to aid interpretation.

---

## 📁 Project Structure

bank-churn-prediction/
│
├── BANK CHURN ANALYSIS.ipynb        # Jupyter notebook with all code and analysis
├── Bank Customer Churn Prediction.csv  # Dataset used for training and evaluation
├── Churn_Report.pdf                 # Final technical report (IEEE format)
├── PowerBI_Visuals.pbix             # Power BI dashboard file (optional)
├── README.md                        # Project overview and instructions
├── requirements.txt                 # Python dependencies (optional)
├── images/                          # Folder for heatmaps and charts used in the report
│   ├── correlation_heatmap.png
│   ├── confusion_matrix_rf.png
│   └── churn_visual_bars.png
└── output/
    ├── model_metrics.txt            # Evaluation scores from trained models
    └── feature_importance.csv       # Ranked features from Random Forest


