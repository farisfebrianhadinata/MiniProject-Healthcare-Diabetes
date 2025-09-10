# MiniProject-Healthcare-Diabetes

### **Diabetes Predictive Analysis: A Machine Learning Case Study**

### **Project Overview**
This project is a data analysis and machine learning case study focusing on a diabetes diagnostic dataset. Its purpose is to build, train, and evaluate a classification model capable of predicting a patient's likelihood of having diabetes based on their historical medical data. The project covers the entire data science workflow, from initial data understanding to the interpretation of modeling results.

### **Workflow**
The project follows a systematic and structured workflow:

1.  **Exploratory Data Analysis (EDA) & Data Understanding**: Initial analysis to understand the structure, distribution, and quality of the data. I checked for missing values (`nulls`), duplicates, and invalid entries, such as `0` in the `BMI` or `Glucose` columns.
2.  **Data Cleaning & Pre-processing**: This phase focused on handling data anomalies. Unreasonable `0` values were replaced with the median to preserve the data's distribution.
3.  **Data Visualization**: Using **Matplotlib** and **Seaborn**, I created various visualizations to discover deep-seated patterns and correlations. These visualizations include *pair plots*, *histograms*, *box plots*, and *correlation heatmaps* that visually represent the relationships between variables. 
4.  **Machine Learning Modeling**: I built two classification models:
    * **Logistic Regression**: A simple, interpretable baseline model.
    * **Random Forest Classifier**: A more complex ensemble-based model that generally offers higher accuracy.
5.  **Model Evaluation**: Model performance was comprehensively evaluated using a **Confusion Matrix** and metrics like **accuracy**, **precision**, **recall**, and **F1-Score**. I also compared the models with **ROC Curves** to assess their overall predictive capability.

### **Key Insights**
* **Glucose, BMI, and Age** were found to be the most significant predictors of diabetes risk.
* The **Random Forest** model outperformed **Logistic Regression** in predicting diabetes outcomes, with a higher **AUC** value.
* Analysis of the Confusion Matrix showed that the model performed well in minimizing **False Negatives**, which is crucial in a medical context to avoid undiagnosed cases of diabetes.

### **Technologies Used**
* **Programming Language**: Python
* **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### **Contact**
For questions or collaboration, please feel free to reach out to me at [farisfebrianhadinata@gmail.com] or on LinkedIn [https://www.linkedin.com/in/faris-febrianhadinata].
