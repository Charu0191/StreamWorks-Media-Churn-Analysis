 # StreamWorks Media: Customer Churn Prediction

## 📊 Overview

Analyzed customer churn patterns for StreamWorks Media, a UK-based streaming platform competing with Netflix & Prime Video.
Using data from 1,500 subscribers across 6 countries, I built predictive models to identify churn drivers and improve retention.

**🏆 Key Finding** : Low watch hours → 3× higher churn risk.

**⚙️ Business Problem** :  **📉 Churn Rate**: 23.4% (351/1500)

## 🎯 Goals :

✅ Identify why customers leave

✅ Predict who’s likely to churn

✅ Recommend retention actions


## 📊 Dataset Summary :

|    Category     |    Description                                                                                   |
| --------------- | ------------------------------------------------------------------------------------------------ |
|  **Records**  | 1,500 subscribers                                                                                |
|  **Regions**  | UK, US, Canada, India, France, Germany                                                           |
|  **Period**   | October 2025                                                                                     |
|  **Features** | Age, Gender, Plan Type, Monthly Fee, Watch Hours, App Usage %, Promotions, Referrals, Complaints |
|  **Target**   | Churn Status (Active / Churned)                                                                  |



<img width="844" height="474" alt="S2" src="https://github.com/user-attachments/assets/b2919268-acec-4452-87d7-459d1e9a877e" />




<img width="845" height="558" alt="S3" src="https://github.com/user-attachments/assets/5b5087b1-bdb6-44f0-b782-a5eea5032c84" />



## 🔬 Methodology :


**1. Data Cleaning & Preparation**

✅ Converted date fields to proper datetime format

✅ Handled missing values using median imputation (10% missing in monthly fees)

✅ Standardized categorical variables for analysis

✅ Created binary encodings for machine learning models


**2. Feature Engineering**

✅ Created strategic features to enhance predictive power :

**Tenure Days** : Customer lifetime with the platform

**Loyalty Flag** : Customers with 6+ months subscription

**Watch-to-Fee Ratio** : Value perception metric

**Heavy Mobile User Flag** : Mobile-dominant behavior indicator

**Age Groups** : Teen, Young Adult, Adult, Mid-age, Senior

**Watch Time Segments** : Low, Medium, High, Very High


**3. Statistical Analysis** 

**T-Tests** : Compared numerical variables between churned and active users

**Chi-Square Tests** : Examined relationships between categorical variables and churn

**Correlation Analysis** : Identified key variable relationships


**4. Predictive Modeling** 

**Logistic Regression** : Churn prediction model

**Linear Regression** : Watch time prediction model

**Class Balancing** : Addressed dataset imbalance for accurate predictions


## 🔍 Key Findings 


**a) Churn Drivers (Statistical Significance)**

✅ Low Engagement is Critical

✅ Churned users watched significantly fewer hours than active users

✅ Average watch hours is the strongest churn predictor


**b) Tenure Matters**

✅ Long-term customers (6+ months) have dramatically lower churn rates

✅ New subscribers represent the highest risk segment


**c) Premium Users Stay Longer**

✅ Premium subscribers churn the least

✅ Basic plan users show highest cancellation rates


**d) Promotions Work**

✅ Users receiving promotional offers are significantly less likely to churn

✅ Referrals also improve retention rates


**e) Price is NOT a Factor**

✅ No significant difference in monthly fees between churned and active users

✅ Engagement and satisfaction matter more than price



**f) High-Risk User Profile**

✅ Low watch time (< 15 hours/month)

✅ Short tenure (< 90 days)

✅ No promotional offers received

✅ Basic subscription tier

✅ High mobile-only usage




## 💡 Key Insights :



|      🔍 Finding                     |           💬 Action                      |
| ----------------------------------- | ---------------------------------------- |
| 📉 Low engagement = 3× higher churn | Personalized onboarding, watch reminders |
| ⏱️ Tenure < 90 days = high churn    | Early retention campaigns                |
| 💰 Price not significant            | Focus on engagement over pricing         |
| 🎁 Promotions reduce churn by 35%   | Target new/basic users                   |
| 📱 Heavy mobile users churn more    | Improve mobile UX & notifications        |


## 🧠 Recommendations : 


1. 🎬 Engage low-watch users in first 30 days

2. 💎 Reward loyal & premium users (exclusive content)

3. 📲 Optimize mobile app experience

4. 🎯 Target new/basic users with promo offers


## 🛠️ Technologies Used


✅ Python 3.8+

✅ pandas - Data manipulation and analysis

✅ numpy - Numerical computations

✅ scikit-learn - Machine learning models

✅ matplotlib & seaborn - Data visualization

✅ scipy - Statistical testing

✅ Jupyter Notebook - Interactive analysis environment

✅ Statistics - T-tests, Chi-square tests, correlation analysis


## 📈 Business Impact :


✅ Clear understanding of churn drivers

✅ Predictive model for at-risk users

✅ Estimated 25–30% churn reduction

✅ £500K+ potential annual savings


<img width="858" height="591" alt="S1" src="https://github.com/user-attachments/assets/c723f5e4-047e-46bc-99f3-af9fef613728" />



## 📧 Contact : 

 **Charu Madaan**

📧 Email: charumadaan88@gmail.com

💼 LinkedIn: linkedin.com/in/charumadaan

🔗 Portfolio: github.com/charumadaan

**Acknowledgments**

Project completed as part of UpTrail Data Analytics Programme

Dataset and business case provided by UpTrail
