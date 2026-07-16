🍷 Wine Quality Prediction using Machine Learning

A Machine Learning project that predicts whether a wine is **GOOD** or **BAD** based on its physicochemical properties. This project demonstrates a complete machine learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, hyperparameter tuning, and feature importance analysis.

🚀 Project Overview

The goal of this project is to classify wine quality into two categories:

- 🟢 **Good Wine** (Quality ≥ 7)
- 🔴 **Bad Wine** (Quality < 7)

Multiple machine learning algorithms were trained and compared to identify the best-performing model for accurate wine quality prediction.

✨ Features

- Exploratory Data Analysis (EDA)
- Missing Value Analysis
- Correlation Heatmap
- Binary Classification
- Feature Scaling using StandardScaler
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Model Comparison
- Hyperparameter Tuning using GridSearchCV
- Feature Importance Analysis
- Performance Evaluation using Multiple Metrics

🛠️ Technologies Used

**Programming Language**
- Python

**Development Environment**
- Google Colab

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

 📊 Dataset

**Dataset:** Wine Quality Dataset

**Features Used**
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

**Target Variable**
- **Good Wine (1):** Quality ≥ 7
- **Bad Wine (0):** Quality < 7

⚙️ Project Workflow

1. Load and Explore Dataset
2. Perform Exploratory Data Analysis (EDA)
3. Check Missing Values
4. Analyze Feature Correlations
5. Convert Quality into Binary Labels
6. Split Data into Training and Testing Sets
7. Train Logistic Regression Model
8. Apply Feature Scaling
9. Compare Logistic Regression, KNN, and Decision Tree
10. Tune the Best Model using GridSearchCV
11. Perform Feature Importance Analysis
12. Evaluate Final Model

🤖 Machine Learning Models

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

1🏆 Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **86.56%** |
| K-Nearest Neighbors (KNN) | **88.13%** |
| Decision Tree | **87.19%** |

**🏅 Best Model:** K-Nearest Neighbors (KNN)

 📁 Project Structure

Wine-Quality-Prediction/
│
├── Wine_Quality_Prediction.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── model_comparison.png
│   └── feature_importance.png
└── dataset/
    └── winequality-red.csv

▶️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Wine-Quality-Prediction.git
```

Navigate to the project directory

```bash
cd Wine-Quality-Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Open the notebook using **Google Colab** or **Jupyter Notebook** and run all cells.

 📌 Future Improvements

- Random Forest and XGBoost implementation
- Deep Learning-based prediction
- Flask/FastAPI web application
- Cloud Deployment (AWS/Azure)
- Explainable AI using SHAP

👩‍💻 Author

**Ganavi S**

Computer Science Engineering Student | Machine Learning & Data Analytics Enthusiast

📧 **Email:** sganavi13@gmail.com

💻 **GitHub:** https://github.com/ganavi0929

🔗 **LinkedIn:** https://www.linkedin.com/in/ganavi-s-03b0262a6 

📜 License

This project is licensed under the **MIT License**.

 ⭐ Support

If you found this project helpful, consider giving this repository a ⭐ on GitHub.

📚 References

- UCI Machine Learning Repository – Wine Quality Dataset
- Scikit-learn Documentation
- Pandas Documentation
- Google Colab Documentation
