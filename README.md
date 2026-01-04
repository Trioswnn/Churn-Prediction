### Churn Prediction

This project aims to address the business problem:

> **How to reduce customer churn in a Telco company by predicting customers’ churn probability.**

The project follows the **CRISP-DM framework**, starting from business understanding to model evaluation with business-oriented conclusions.

Three evaluation metrics are used to assess the model performance:

* **Recall** — to measure how many actual churn customers can be successfully detected and retained
* **Precision** — to evaluate cost efficiency by minimizing unnecessary retention incentives
* **AUC (ROC)** — to assess the model’s overall ability to distinguish churn and non-churn customers regardless of classification threshold

A business simulation is conducted to translate model performance into **cost and revenue impact**, showing that:

* **Precision controls retention cost**
* **Recall drives revenue recovery**
* **AUC ensures the model is reliable for probability-based decision making**

This project emphasizes that in churn prediction, **business-aligned evaluation metrics are more important than accuracy alone**.
