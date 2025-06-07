# Laptop-Price-Prediction-ML-Project
This project focuses on developing machine learning model to predict laptop prices accurately for SmartTech Co.
🚀 **Objectives:**
- Accurately predict laptop prices based on technical specifications.
- Understand the impact of different features (brand, RAM, processor, etc.) on pricing.
- Enable real-time price prediction for newly released laptops.
- Ensure the model is interpretable for business use.

🛠 **Project Workflow:**
1. **Data Exploration**
   - Initial overview using Pandas and Seaborn
   - Identifying patterns and feature distributions

2. **Data Preprocessing**
   - Removing irrelevant columns
   - Handling missing values
   - Data type corrections

3. **Feature Engineering**
   - Extracting key information from textual features
   - Creating new variables like `Touchscreen`, `IPS`, `CPU brand`

4. **Modeling**
   - Tried multiple models: Linear Regression, Decision Tree Regressor, RandomForest Regression, Support Vector Regressor(SVR) and XGBoost Regressor	
   - Model evaluation based on RMSE and R² Score

5. **Interpretability**
   - Analyzed feature importance to understand price drivers

🧠 **Key Learnings:**

- High-end features (SSD, GPU, CPU brand) strongly influence laptop prices.
- The brand plays a significant role in price, even for similar specs.
- RandomForest Regression and XGBoost Regressor offered better performance than basic models.
