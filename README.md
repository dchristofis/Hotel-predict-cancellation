# Hotel-predict-cancellation
# **Overview**
This project aims to develop predictive models to forecast whether a customer will cancel their hotel booking or not. By leveraging data analytics and machine learning techniques, these models can analyze historical booking patterns, customer behavior, and other relevant factors to anticipate cancellations. 

# **Business Value - Purpose**
This initiative holds immense business value as it enables hotels to optimize resource allocation, improve revenue management strategies, and enhance customer satisfaction by preemptively addressing potential cancellations, thereby reducing revenue loss and optimizing operational efficiency.


### **1. Optimizing Resource Allocation:**
Predicting cancellations aids in efficiently scheduling staff, managing room inventory, and optimizing housekeeping services, preventing both overstaffing and underutilization, thus enhancing operational efficiency and reducing costs.

### **2. Improving Revenue Management Strategies:**
Anticipating cancellations allows for dynamic pricing adjustments and strategic room allocation, maximizing revenue potential and ensuring optimal profitability in fluctuating market conditions.

### **3. Enhancing Customer Satisfaction:**
Proactively addressing potential cancellations enables timely engagement with guests to resolve issues, fostering positive guest experiences, loyalty, and favorable reviews.

### ** 4. Reducing Revenue Loss:**
Accurate cancellation predictions help hotels minimize revenue loss by implementing preventive measures, such as adjusting policies or reallocating resources, safeguarding revenue streams and business stability.


**Methods Used**
1. Python

2. Data Cleaning
To ensure accuracy and reliability, the dataset undergoes a thorough data cleaning process. This involves handling missing values, removing duplicates, and addressing any anomalies in the data.

3. Eda & Visualizations
Used to see correlation betweens features and extract usefull insights for building my models.

4. Using get_dummies to deal with categorical data

5. Train_test_split 
Splits your dataset into training and testing sets. This is essential for assessing the model's performance on unseen data. 

6. Use StandardScaler() to transforme my data so that it fits within a specific scale

7. RandomForestClassifier, AdaBoostClassifier, XGBClassifier, LGBMClassifier
Building my models

8. Parameters tuning: Improving models finding the best blend of parameters for each of models

9. Feature importance
Using feature_importances_ and Shap method to keep most important features which influence more my models