# Employee Attrition Prediction using Decision Tree and Random Forest Classification

## Objective

The objective of this project is to develop Decision Tree and Random Forest classification models to predict employee attrition based on demographic, professional, and work-related attributes. The performance of both models is compared to determine which algorithm provides better prediction accuracy and reliability.

---

## Dataset Link

**Dataset Name:** IBM HR Analytics Employee Attrition & Performance Dataset

**Kaggle Link:**  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

The project was completed using the following steps:

1. Imported the required Python libraries.
2. Loaded the IBM HR Analytics Employee Attrition & Performance dataset using Pandas.
3. Explored the dataset by displaying the first five records, dataset information, and summary statistics.
4. Checked for missing values in the dataset.
5. Encoded all categorical variables using Label Encoding.
6. Selected the input features and target variable (Attrition).
7. Split the dataset into **80% training** and **20% testing** sets.
8. Trained a Decision Tree Classifier.
9. Trained a Random Forest Classifier using **100 estimators**.
10. Predicted employee attrition using both models.
11. Evaluated both models using Accuracy Score, Precision, Recall, F1-Score, and Confusion Matrix.
12. Compared the performance of both models.
13. Generated the Feature Importance plot for the Random Forest model.

---

## Results

Both the Decision Tree and Random Forest classifiers successfully predicted employee attrition. The models were evaluated using Accuracy Score, Precision, Recall, F1-Score, and Confusion Matrix. The Random Forest classifier achieved better overall performance than the Decision Tree classifier by providing higher evaluation metric values and fewer classification errors. The Feature Importance analysis also identified the most influential factors affecting employee attrition.

---

## Model Comparison

| Evaluation Metric | Decision Tree | Random Forest |
|-------------------|--------------|---------------|
| Accuracy | Good | Better |
| Precision | Good | Better |
| Recall | Good | Better |
| F1-Score | Good | Better |

### Comparison Summary

- Both Decision Tree and Random Forest models successfully classified employee attrition.
- The Random Forest classifier achieved higher Accuracy, Precision, Recall, and F1-Score than the Decision Tree classifier.
- Random Forest reduced overfitting by combining predictions from multiple decision trees.
- The Feature Importance plot highlighted the most significant employee attributes influencing attrition.
- Overall, the Random Forest model provided more accurate and reliable predictions than the Decision Tree model.

---

## Conclusion

This project demonstrates that both Decision Tree and Random Forest are effective machine learning algorithms for predicting employee attrition. However, the Random Forest classifier outperformed the Decision Tree classifier by achieving better Accuracy, Precision, Recall, and F1-Score. Random Forest combines multiple Decision Trees to reduce overfitting and improve prediction performance, making it more robust and reliable. Although Decision Trees are simple and easy to interpret, they are more likely to overfit complex datasets. On the other hand, Random Forest requires greater computational resources and longer training time due to the construction of multiple trees. Overall, Random Forest proved to be the better model for predicting employee attrition in this dataset.
