
🏦 Loan Approval Prediction (Machine Learning)
A focused Machine Learning classification project using Python and Scikit-learn to build a predictive model for loan approval status, demonstrating proficiency in data preprocessing, feature engineering, and model evaluation.

🎯 Model Performance Summary
The primary model, Logistic Regression, established a strong baseline for classification performance:

Metric	Model	Score	Business Interpretation
Accuracy (Test Set)	Logistic Regression	78.86%	The model correctly predicts the approval status nearly 8 out of 10 times.

🔑 Key Predictive Insights
The analysis identified the most influential factors in determining loan approval status:

Rank	Feature	Absolute Coefficient	Business Insight
1	Credit_History	2.92	The single most powerful factor; a reliable credit history is overwhelmingly crucial for approval.
2	Property_Area_Semiurban	0.70	Living in a Semiurban area significantly increases the likelihood of loan approval.
3	Married_Yes	0.59	Being married is a strong factor that positively influences the approval decision.


🛠️ Technical Workflow
Data Preprocessing: Handled missing values by imputing categorical features with the mode and numerical features (Loan Amount) with the median.

Feature Engineering: Converted all categorical variables (Gender, Education, Property Area, etc.) into a numerical format suitable for the model using One-Hot Encoding and Label Encoding.

Modeling: Used Logistic Regression to establish a strong baseline and extract feature coefficients as a proxy for importance.
