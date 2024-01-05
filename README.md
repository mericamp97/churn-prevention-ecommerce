# Churn Prevention in E-Commerce
This repository contains our project on churn prevention for an e-commerce dataset. Our aim is to identify patterns and factors that contribute to customer churn and create ML models to predict and prevent it.

# Project Overview
Our project is divided into several stages, with each stage addressing a specific aspect of the problem:
**1. Data Pre-processing:** Preparing the data for modeling by handling missing values, encoding categorical variables, and normalizing features. (Contributed by Sidharth Pahuja)
**2. Exploratory Data Analysis (EDA):** An in-depth analysis of the dataset to understand the characteristics and distribution of data.
**3. Model Development:**
  **3.1. Logistic Classifier Model:** A logistic regression model for churn prediction. (Contributed by Sidharth Pahuja)
  **3.2. LinearSVC:** A Support Vector Classifier model implemented with a linear kernel. (Contributed by Sidharth Pahuja)
  **3.3. Decision Tree Models:** A series of decision tree models to explore different aspects of the data.
  **3.4. Random Forest Model:** An ensemble model using random forests for better prediction accuracy.
  **3.5. Gradient Boosting Classifier Model:** An advanced ensemble technique for improved prediction performance. 
**4. Value Matrix and Model Comparison:** A comparative study of all the models to evaluate return on investment of a churn prevention campaign. 

# Project Conclusion
The model that we expect to drive highest revenue per customer is the random forest with GradienSearch, and considering all features in each tree of the forest (i.e., max_features = None).

# Data
The dataset used in this project is ecommerce_data.csv, which contains various features related to customer behavior and transactions in an e-commerce setting. This data  has been obtained from Kaggle. Link: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

# Notebook
The churn-prevention-ecommerce.ipynb notebook contains all the code and analysis for this project.

# Acknowledgements
Special thanks to my colleague Sidharth Pahuja, who contributed to this project with the data pre-processing, logistic classifier model, and linearSVC, but is not present on GitHub.
