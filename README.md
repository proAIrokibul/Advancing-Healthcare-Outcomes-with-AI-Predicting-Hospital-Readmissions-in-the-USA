# Advancing-Healthcare-Outcomes-with-AI-Predicting-Hospital-Readmissions-in-the-USA

## **Project Description**
Predicting hospital readmissions is crucial for improving healthcare outcomes and reducing unnecessary costs. This project leverages machine learning to predict hospital readmission in the USA using a dataset that includes patient demographics, medical history, and hospitalization details. The goal is to identify patients at high risk of readmission, enabling hospitals to provide targeted interventions.

### **Dataset Details**
The dataset contains the following columns:
- **age**: Age of the patient  
- **gender**: Gender of the patient  
- **primary_diagnosis**: Patient's primary medical diagnosis  
- **num_procedures**: Number of medical procedures performed  
- **days_in_hospital**: Total number of days spent in the hospital  
- **comorbidity_score**: A score representing the severity of existing medical conditions  
- **discharge_to**: Discharge destination of the patient  
- **readmitted**: Target variable indicating whether the patient was readmitted (1 = yes, 0 = no)  

### **Key Tasks**
1. **Data Preprocessing**: Handling categorical variables, missing values, and feature scaling.  
2. **Exploratory Data Analysis (EDA)**: Creating visualizations to uncover trends and patterns.  
3. **Modeling**: Applying three machine learning algorithms (Logistic Regression, Random Forest, and Gradient Boosting) and comparing their performance.  
4. **Evaluation and Visualization**: Evaluating models using accuracy, precision, recall, and F1-score, and visualizing the results for easy interpretation.  

---

## **Model Results**
### Logistic Regression
- **Accuracy**: 50.1%  
- **Precision (class 1)**: 0.19  
- **Recall (class 1)**: 0.49  
- **F1-Score (class 1)**: 0.27  

### Random Forest
- **Accuracy**: 80.3%  
- **Precision (class 1)**: 0.15  
- **Recall (class 1)**: 0.01  
- **F1-Score (class 1)**: 0.02  

### Gradient Boosting
- **Accuracy**: 81.1%  
- **Precision (class 1)**: 0.00  
- **Recall (class 1)**: 0.00  
- **F1-Score (class 1)**: 0.00  

While all models performed reasonably well on classifying the majority class (class 0), they struggled to correctly predict the minority class (class 1), highlighting the need for techniques like class balancing or advanced feature engineering.

---

## **Business Impact**
### 1. Improved Patient Care
By identifying patients at high risk of readmission, hospitals can provide tailored post-discharge care, reducing complications and enhancing recovery.

### 2. Cost Reduction
Hospital readmissions are costly. Predictive insights can help allocate resources more effectively, reducing financial burdens on healthcare providers and insurers.

### 3. Regulatory Compliance
Many healthcare systems are penalized for excessive readmissions. This solution helps hospitals avoid such penalties by proactively managing readmission risks.

### 4. Operational Efficiency
With data-driven decision-making, hospitals can optimize discharge planning, patient follow-ups, and resource allocation.

### 5. Patient Satisfaction
A reduction in readmission rates translates to better patient outcomes, leading to higher satisfaction and trust in healthcare services.

---

## **Conclusion**
This project demonstrates the transformative potential of machine learning in healthcare by addressing a critical issue—hospital readmissions—and providing actionable insights that benefit both patients and providers. Further improvements, such as handling class imbalance and advanced feature engineering, can enhance the model's predictive power and overall utility.
