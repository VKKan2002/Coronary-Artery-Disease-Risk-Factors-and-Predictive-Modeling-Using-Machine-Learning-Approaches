# Coronary-Artery-Disease-Risk-Factors-and-Predictive-Modeling-Using-Machine-Learning-Approaches

Coronary Artery Disease Risk Prediction Using Machine Learning
Summary
This study explores the application of machine learning approaches to predict coronary artery disease (CAD), which accounts for nearly 40% of all cardiovascular disease deaths in the United States. The research demonstrates how ensemble machine learning methods can effectively identify patients at risk for CAD using clinical and diagnostic features.
Methodology

Dataset: Used the consolidated UCI Heart Disease dataset (1,109 patient records from 4 medical centers)
Features: 14 clinical variables including age, chest pain type, blood pressure, cholesterol, ECG results, and exercise stress test parameters
Models Evaluated: Logistic Regression, Decision Tree, Random Forest, AdaBoost, Gradient Boosting, and XGBoost
Preprocessing: Applied SMOTE for class balancing, handled missing values, and performed feature scaling
Validation: 5-fold cross-validation with hyperparameter tuning using RandomizedSearchCV

Key Results

Best Performance: Random Forest achieved the highest ROC-AUC of 0.9353, followed by Gradient Boosting (0.9346)
Most Important Features: ST segment slope, chest pain type, and ST depression emerged as top predictors
Clinical Relevance: Results align with established cardiac diagnostic markers, validating model interpretability
High Sensitivity: All models maintained strong recall (>0.89), crucial for medical screening applications

Clinical Impact
The study demonstrates that machine learning can effectively complement traditional cardiovascular risk assessment tools. The identified predictive features correspond to well-established clinical indicators of myocardial ischemia, supporting the potential for real-world clinical implementation.
Limitations & Future Work

Dataset limited to CAD outcomes (doesn't include other CVD conditions)
Potential multicollinearity between ECG-related features not formally assessed
Need for external validation on larger, more diverse populations
Recommendation to extend to longitudinal prediction models

This research provides a reproducible framework for cardiovascular risk prediction that could be adapted for broader CVD screening and prevention strategies.
