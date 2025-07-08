# 🫀 Heart Failure Mortality Prediction using Machine Learning

This project uses supervised machine learning algorithms to predict mortality outcomes in heart failure patients based on clinical records. It covers preprocessing, training, evaluation, resampling techniques, and explainable AI for insights into individual predictions.

---

## 📂 Project Structure

- `heart_failure_prediction.ipynb` – Main notebook with complete code, analysis, and visualizations.
- `requirements.txt` – List of Python packages needed (optional but recommended).
- `heart_failure_clinical_records.csv` – Dataset used (you can upload or link it from Kaggle/UCI).

---

## 🧠 Models Implemented

1. **Support Vector Machine (SVM)**
2. **Decision Tree**
3. **Gaussian Naive Bayes**
4. **Random Forest**
5. **XGBoost**
6. **AdaBoost**
7. **Artificial Neural Network (ANN with Keras)**

---

## 🔄 Additional Techniques

- **SMOTE**: To balance the class distribution and improve classifier performance.
- **LIME (Local Interpretable Model-Agnostic Explanations)**: For explaining **why** the model predicted a certain outcome on individual cases (e.g., why a death was wrongly predicted).

---

## 📊 Evaluation Metrics

- ROC AUC Score
- Confusion Matrix
- Precision, Recall, F1-Score

---

## ⚙️ How to Run

1. Clone the repository or download the `.ipynb` file.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   
Or manually:

1. Launch Jupyter Notebook or run on Google Colab.
2. Run all cells in order.

---

## 📈 Key Findings
- XGBoost and Random Forest yielded the highest ROC AUC scores.
- SMOTE significantly improved the performance of Gaussian NB and AdaBoost.
- LIME helped interpret misclassifications made by the ANN.

---

## 🪪 License
This project is open-sourced under the MIT License.

---

## 🙋‍♂️ Author
Shilajit Mukherjee
- Data Science student at IIT Madras

For queries, feel free to reach out!
