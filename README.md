# ChurnScope — Customer Churn Prediction

ChurnScope is a machine learning project focused on predicting customer churn by analyzing customer demographics, account information, and service usage patterns.

## 🎯 Project Objective

The goal is to identify customers who are more likely to discontinue a service and understand the factors associated with customer churn using machine learning.

## 📊 Dataset

This project uses the **Telco Customer Churn** dataset, which contains customer information such as:

- Customer demographics
- Account and service details
- Contract types and payment methods
- Tenure and monthly charges
- Customer churn status

**Target variable:** `Churn` — whether a customer has left the service.

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 🤖 Machine Learning Models

The project explores and compares:

- **Logistic Regression** — a baseline classification model.
- **Random Forest** — an ensemble learning model for classification.

Model performance will be evaluated using appropriate classification metrics, including accuracy, precision, recall, F1-score, and ROC-AUC.

## 📁 Project Structure

```text
churnscope/
├── Churn_Analysis_Using_Logistic_Regression.ipynb
├── Churn_Analysis_Using_Random_Forest.ipynb
├── README.md
└── LICENSE
```

## 🚀 Current Status

The project is under development. Current work focuses on data preprocessing, exploratory data analysis, model training, and performance evaluation.

## 🔮 Future Improvements

- Compare model performance and feature importance.
- Build an interactive dashboard for churn insights.
- Develop an API to serve predictions.
- Integrate the model into a full-stack web application.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Note:** The dataset is provided by a third party. Please refer to its original source and applicable terms before redistributing it.
