# Heart-Disease-Prediction-Using-Python
### Heart Disease Prediction Model Using Python

This project focuses on predicting heart disease using machine learning techniques, specifically Logistic Regression and Decision Tree classifiers. The implementation follows a structured approach to preprocess the data, train the models, and evaluate their performance. Below is a detailed overview:

---

### **1. Data Preprocessing**
- **Data Cleaning:** The dataset was checked for missing or inconsistent values, and appropriate imputation or removal methods were applied.
- **Normalization:** Continuous variables were normalized to ensure uniform scaling, improving the performance of the algorithms.
- **Feature Engineering:** Relevant features were selected, and categorical variables (if any) were encoded.

---

### **2. Data Splitting**
- The dataset was split into **training (70%)** and **testing (30%)** subsets to evaluate the model’s performance effectively.

---

### **3. Logistic Regression**
- **Training:** A Logistic Regression model was trained on the normalized training dataset.
- **Evaluation Metrics:**
  - **Confusion Matrix:** The confusion matrix was derived to evaluate true positives, false positives, true negatives, and false negatives.
  - **Accuracy:** Logistic Regression achieved an accuracy of approximately **84%**, outperforming the Decision Tree model.
- **Visualization:** Relevant graphs were plotted, including the decision boundary and metrics like the ROC curve to analyze performance.

---

### **4. Decision Tree**
- **Training:** A Decision Tree classifier was trained on the same dataset for comparison.
- **Evaluation Metrics:**
  - Confusion Matrix was used to identify performance in terms of false positives, false negatives, true positives, and true negatives.
  - Decision Tree results were less accurate compared to Logistic Regression.
- **Visualization:** Plots such as the tree structure and feature importance were generated for interpretability.

---

### **5. Results**
- Logistic Regression emerged as the **more accurate model** with an accuracy of **84%**, making it a suitable choice for predicting heart disease.
- Decision Tree showed less accurate results, highlighting the importance of selecting an appropriate algorithm for specific datasets.

---

### **Conclusion**
The analysis demonstrates the utility of machine learning for heart disease prediction. The model can assist healthcare professionals in identifying high-risk individuals, allowing timely interventions. Future enhancements could include hyperparameter tuning, exploring ensemble methods, and expanding the dataset for even better accuracy.
