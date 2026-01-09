# Customer Churn Prediction: Saving $45k in Monthly Revenue

Status: ✅ Completed | Type: Classification & Business Strategy
1. Business Problem

The client, a Telecom provider, is facing a high churn rate (26%). Acquiring a new customer costs 5x more than retaining an existing one. The goal of this project was to identify high-risk customers before they leave and develop a retention strategy.
2. The Solution

I built a Random Forest Classifier that predicts the probability of a customer churning with 82% Accuracy.

Key Technical Steps:

    Preprocessing: Handled missing values and used One-Hot Encoding for categorical variables.

    Modeling: Tuned a Random Forest model (n_estimators=100) to prioritize Recall (catching as many churners as possible).

    Feature Analysis: Identified "Month-to-month contracts" and "Fiber Optic internet" as the top predictors of churn.

3. Key Insights (The "Why")

(Insert your Feature Importance Plot here)

    Insight 1: Customers on Month-to-month contracts are 5x more likely to churn.

    Insight 2: Electronic Check users have a higher dissatisfaction rate.

4. Strategic Recommendation

Target high-risk customers (Prob > 70%) with a "1-Year Contract Upgrade Offer" (20% discount).

    Projected ROI: Saving 100 customers/month = $4,000 net monthly savings.

5. Tech Stack

Python Pandas Scikit-Learn Seaborn
