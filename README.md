# Water Quality Prediction Model

This repository contains a machine learning model to predict the potability of water based on various water quality features. The goal is to determine whether the water is potable (safe to drink) based on measurements such as pH, turbidity, and chemical content.

---

## Dataset Features

The dataset consists of the following columns:

1. **pH**: The pH level of the water, indicating its acidity or alkalinity.
2. **Hardness**: The amount of dissolved calcium and magnesium in the water, affecting its "hardness."
3. **Solids**: The total dissolved solids in the water, which could indicate contamination levels.
4. **Chloramines**: The presence of chloramines, a compound formed by the reaction of chlorine with ammonia, used in water treatment.
5. **Sulfate**: The level of sulfate ions in the water, which may indicate the presence of pollutants.
6. **Conductivity**: The ability of the water to conduct electricity, related to the concentration of dissolved ions.
7. **Organic_carbon**: The level of organic carbon in the water, which could indicate the presence of organic contaminants.
8. **Trihalomethanes**: A group of chemicals that can form as by-products of chlorinating water, potentially harmful at high levels.
9. **Turbidity**: A measure of water clarity, higher turbidity can indicate pollution or the presence of suspended solids.
10. **Potability**: The target variable, indicating whether the water is potable (safe to drink, typically a binary classification of 1 for potable or 0 for non-potable).

---

## Models Tested
1. **Logistic Regression**
2. **Logistic Regression (L1)**
3. **Logistic Regression (L2)**
4. **KNN Classifier**
5. **SVM Classifier**
6. **Decision Tree**
7. **Random Forest**
8. **Naive Bayes**
9. **Gradient Boosting**
10. **AdaBoost**

---

## Performance Metrics
- **Accuracy**: Proportion of correctly classified instances.
- **Precision**: The proportion of positive predictions that are actually correct.
- **Recall**: The proportion of actual positive instances that were identified correctly.
- **F1 Score**: The harmonic mean of precision and recall.
- **ROC-AUC**: Area under the ROC curve, representing the likelihood of the classifier distinguishing between classes.

---

## Model Performance

| Model                   | Accuracy | Precision | Recall  | F1 Score | ROC-AUC |
|--------------------------|----------|-----------|---------|----------|---------|
| Logistic Regression      | 0.6098   | 0.0000    | 0.0000  | 0.0000   | 0.5484  |
| Logistic Regression (L1) | 0.6098   | 0.0000    | 0.0000  | 0.0000   | 0.5485  |
| Logistic Regression (L2) | 0.6098   | 0.0000    | 0.0000  | 0.0000   | 0.5484  |
| KNN Classifier           | 0.6113   | 0.5031    | 0.3203  | 0.3914   | 0.5991  |
| SVM Classifier           | 0.6692   | 0.6970    | 0.2695  | 0.3887   | 0.6481  |
| Decision Tree            | 0.6326   | 0.6119    | 0.1602  | 0.2539   | 0.5656  |
| Random Forest            | 0.6555   | 0.6154    | 0.3125  | 0.4145   | 0.6430  |
| Naive Bayes              | 0.6143   | 0.5161    | 0.1875  | 0.2751   | 0.6088  |
| Gradient Boosting        | 0.6509   | 0.6364    | 0.2461  | 0.3549   | 0.6560  |
| AdaBoost                 | 0.6189   | 0.6000    | 0.0703  | 0.1259   | 0.5823  |


---

## Key Insights
- **Best Accuracy**: SVM Classifier with 0.6692
- **Best Precision**: SVM Classifier with 0.6970
- **Best Recall**: KNN Classifier with 0.3203
- **Best F1 Score**: Random Forest with 0.4145
- **Best ROC-AUC**: Gradient Boosting with 0.6560

---

## Conclusion
- The **SVM** model performs best in terms of precision, whereas **KNN** has the highest recall.
- **Random Forest** achieves the best F1 score, making it a strong candidate for balancing precision and recall.
- **Gradient Boosting** stands out in terms of ROC-AUC, suggesting it has a better overall ability to distinguish between classes.

---

## Streamlit Cloud Deployment

You can try out the model and make predictions on water potability directly from the web using the following link:

[**Water Potability Check App**](https://kavinkumartk-water-potability-check-app-0qqe56.streamlit.app/)

---

## Setup Instructions

1. **Clone the repository:**

   git clone <https://github.com/kavinkumartk/Water-Potability-Check>

---

AUTHOR:KAVINKUMAR T
GITHUB LINK:https://github.com/kavinkumartk

---
