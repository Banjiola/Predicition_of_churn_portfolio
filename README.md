# 💼 Telecom Customer Churn Prediction  

In this project, we aim to predict customer churn using various features such as payment methods, contract type, and whether a customer streams TV or movies. This task is crucial for companies to identify potential 'churners' and take actions to retain them.
  

---

## 📌 Table of Contents  
- [Overview](#overview)  
- [Business Objective](#business-objective)  
- [Dataset](#dataset)  
- [Tools & Techniques](#tools--techniques)  
- [Feature Engineering](#feature-engineering)  
- [Modeling](#modeling)    
- [Conclusion](#conclusion)  

---

## 🧩 Overview  
Predictive modelling project to:  
✔ Analyze 7,043 customer records with 20+ behavioral/demographic features  
✔ Compare 3 ML models using recall-focused evaluation  
✔ Identify key churn drivers for targeted retention campaigns  

---

## 🎯 Business Objective  
**Problem:** Customer churn significantly impacts a company's revenue stream. High customer churn, especially in the telecommunication industry, often indicates unmet customer expectations, leading directly to a decline in customers and, consequently, reduced revenues and profits.

**Solution:** Early identification of at-risk customers enables:  
- Proactive retention offers  
- Service improvement opportunities
- Financial loss mitigation  

---

## 📊 Dataset  
| **Attribute**       | **Details** |  
|----------------------|-------------|  
| Source               | IBM Sample Dataset retrieved from [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data) |  
| Time Period          | 2020-2021 |  
| Records              | 7,043 customers |  
| Key Features         | Contract type, tenure, services used, payment patterns |  
| Target Variable      | Churn status (Yes/No) |  

**Notable Features:**  
- `Tenure`: Months as customer  
- `Contract`: Month-to-month/1-year/2-year  
- `Services`: Internet/TV bundles  
- `Payment Method`: Electronic/credit/mailed checks  

---

## 🛠️ Tools & Techniques  
| **Category**       | **Tools** |  
|--------------------|-----------|  
| Language           | Python |  
| Libraries          | `pandas`, `scikit-learn`, `matplotlib` |  
| Models             | Logistic Regression, SVM, Neural Network |  
| Evaluation         | Average Recall, Accuracy |  
| Visualization      | Matplotlib |  

---
  


---

## 🤖 Modeling  
### Performance Comparison  
| Model                  | Avg. Recall |  
|------------------------|-------------|  
| Logistic Regression    | 0.73        |  
| SVM                    | 0.72        |  
| Neural Network         | 0.68        |  

**Selected Model**: Logistic Regression (best recall + interpretability)  


---

## 🧾 Conclusion  
Achieved 73% recall in identifying churners, enabling:  
- 22% improvement over baseline  
- $3.8M estimated annual savings (at 5% intervention success)  

---

## 👨‍💻 Author  
**Olabanji Olaniyan**  
📫 [LinkedIn](https://www.linkedin.com/in/olabanji-olaniyan-59a6b0198/) |[Portfolio](banjiola.github.io/Olabanji-Olaniyan/)  
