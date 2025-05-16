 💳 Credit Card Fraud Detection using Machine Learning

This project is focused on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, and various techniques were used to handle this and build an effective classifier.

 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Description: This dataset contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, with only 492 cases of fraud (0.17%).

 🛠️ Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost / Random Forest / Logistic Regression (or your model of choice)

 📌 Project Highlights

- Performed EDA and handled class imbalance using under-sampling / SMOTE.
- Visualized data using correlation heatmaps, class distributions, PCA, and more.
- Trained multiple machine learning models.
- Evaluated with confusion matrix, accuracy, precision, recall, F1 score, and ROC-AUC.
- Achieved high recall and AUC, crucial for detecting fraud with minimal false negatives.

 📈 Visualizations

Here are a few sample visualizations included in the notebook:
- Class distribution plot
- Correlation heatmap
- PCA-based fraud clustering
- Confusion matrix
- ROC-AUC curve

🔍 Model Evaluation Metrics

| Metric        | Score (example) |
|---------------|-----------------|
| Accuracy      | 99.5%           |
| Precision     | 88.6%           |
| Recall        | 92.3%           |
| F1 Score      | 90.4%           |
| AUC-ROC       | 0.97            |

> Note: These scores may vary depending on your preprocessing and model choice.

🚀 How to Run

1. Open the notebook on Google Colab.
2. Upload the dataset (CSV file from Kaggle).
3. Run the cells step by step.



