💰 Bank Term Deposit Prediction using Logistic Regression

📌 Project Overview

This project aims to predict whether a customer will subscribe to a term deposit based on their banking behavior using a **Logistic Regression model**.

---

📂 Dataset Description

* Dataset: Bank Marketing Dataset
* Features: **17 attributes**
* Target Variable:

  * **y = yes/no** (subscription status)
* Includes:

  * Demographics (age, job, marital status)
  * Financial details (balance, loan, etc.)
  * Campaign-related information

---

⚙️ Methodology

🔹 1. Data Preprocessing

* Loaded CSV file using pandas
* Handled categorical variables using **Label Encoding**
* Checked dataset structure and cleaned data

---

🔹 2. Feature Selection

* Input Features (X): All attributes except target
* Target Variable (y): Subscription (yes/no)

---

🔹 3. Model Used: Logistic Regression

* Suitable for **binary classification**
* Predicts probability using sigmoid function

---

🔹 4. Training Strategy

* Train-test split: **80% training / 20% testing**
* Model trained using `scikit-learn`

---

🔹 5. Evaluation Metrics

* Accuracy
* Classification Report:

  * Precision
  * Recall
  * F1-score
* Confusion Matrix

---

📊 Results & Findings

* The model achieved reasonable accuracy in predicting customer behavior.
* Logistic Regression provides interpretable results and works well for structured data.

✅ Key Insight:

Customer subscription behavior can be predicted using historical data, which can help banks target potential customers more effectively.

---

🚀 Future Improvements

* Use **One-Hot Encoding** instead of Label Encoding
* Handle class imbalance (important!)
* Try advanced models:

  * Random Forest
  * Gradient Boosting
* Perform feature scaling for better performance

---

🧾 Conclusion

This project demonstrates how machine learning can support decision-making in banking by predicting customer behavior. Logistic Regression provides a simple yet effective baseline model.

---

