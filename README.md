# Credit Risk Modeling

## 1. About the Dataset
This project focuses on developing a classification model to optimize credit risk. The dataset includes various financial features related to credit applications, which are used to predict the likelihood of credit risk and improve decision-making processes.

## 2. Objective
The primary objectives of this project are to:
- Develop a classification model to optimize credit risk.
- Enhance model performance through hyperparameter tuning.
- Evaluate and improve the model using statistical and machine learning techniques.

## 3. Approach
The project follows these steps:
- **Statistical Analysis:**
  - Performed χ² (Chi-square), ANOVA (Analysis of Variance), and Variance Inflation Factor (VIF) tests to address multi-collinearity.
  - Applied SMOTE (Synthetic Minority Over-sampling Technique) to reduce class imbalance and improve model training.
- **Data Visualization & Transformation:**
  - Visualized data using Box plots and Local Outlier Factor (LOF) to detect and address outliers.
  - Used the Kolmogorov-Smirnov (KS) test and Box-Cox transformation to check and address distribution issues.
- **Model Building:**
  - Created a preprocessing pipeline to streamline data preparation.
  - Applied various classification ensemble models including Decision Trees, Support Vector Machines (SVM), and XGBoost.
  - Conducted hyperparameter tuning to optimize model performance.
- **Evaluation:**
  - Evaluated the models using key performance indicators (KPIs) such as accuracy and F1-score.

## 4. Results & Key Features
- **Best Performance:** Among the classifiers tested, the best model achieved an accuracy of 0.77 and an F1-score of 0.76.
- **Model Comparison:** Compared the performance of Decision Trees, SVM, and XGBoost to determine the most effective approach for credit risk classification.

## 5. License
This project is licensed under the MIT License.

## 6. Contact
For any questions or feedback regarding this project, please contact:
- **Vivek Radadiya**
