
# 💳 Credit Card Fraud Detection Using Machine Learning

## 📂 Dataset

**Source:** Kaggle – Credit Card Fraud Detection Dataset 2023

**Records:** 550,000+ transactions

**Features:** 30 variables (V1–V28, Amount, Class)

**Target:** Class (0 = Legitimate Transaction, 1 = Fraudulent Transaction)

The dataset contains anonymized transaction features and is highly imbalanced, with fraudulent transactions representing a very small percentage of all records.

## 🛠️ Data Preprocessing

* Checked for missing values and duplicates.
* Split data into training and testing sets (80:20).
* Applied **StandardScaler** for feature normalization.
* Used **SMOTE** to balance the minority fraud class.
* Prepared scaled datasets for model training and evaluation.

## 📊 Exploratory Data Analysis (EDA)

* Analyzed fraud vs. non-fraud transaction distribution.
* Visualized transaction amounts using histograms and boxplots.
* Generated correlation heatmaps to identify feature relationships.
* Examined class imbalance and transaction patterns.

## 🔬 Modeling

### Support Vector Machine (SVM)

* Trained Linear and RBF kernel models.
* Performed cross-validation to identify optimal parameters.
* Evaluated performance using classification metrics.

### Random Forest

* Built an ensemble classifier for fraud detection.
* Compared results with SVM.

### XGBoost

* Implemented gradient boosting for improved prediction accuracy.
* Tuned parameters and evaluated performance against other models.

## 📈 Performance Evaluation

Models were assessed using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

Special emphasis was placed on Recall and F1-Score due to the importance of identifying fraudulent transactions.

## 📌 Conclusion

The project demonstrates the effectiveness of machine learning in detecting credit card fraud. SMOTE improved minority class prediction, while ensemble models such as Random Forest and XGBoost provided strong classification performance. The developed system can support financial institutions in reducing fraud-related losses and improving transaction security.


