📊 Telecom Customer Churn Analysis & Prediction
🚀 Project Overview:
This project performs an Exploratory Data Analysis (EDA) and Data Preprocessing on a Telecommunications dataset to identify why customers are leaving (churning) and prepare the data for predictive modelling. Customer churn is a critical metric for telecom companies. By understanding the patterns behind churn, businesses can implement retention strategies to keep high-value customers.
🛠️ Key Data Insights: Contract Type: 
High churn rates are observed in Month-to-month contracts compared to long-term commitments. 
Service Impact: Customers without Tech Support and Online Security are significantly more likely to churn.
Payment Methods: Users paying via Electronic Check show a much higher churn frequency than those using automatic payment methods.
Price Sensitivity: A positive correlation exists between higher Monthly Charges and the likelihood of churn, specifically for Fiber Optic users.
🧠 Data Preprocessing Steps: 
To make the data "Machine Learning ready," the following steps were performed: 
Handling Missing Values: Identified and removed rows with empty TotalCharges.
Feature Simplification: Merged redundant categories (e.g., "No internet service") into a simple "No" to reduce noise.
Encoding: 
Binary Encoding: Converted Yes/No and Gender to 1/0.
One-Hot Encoding: Transformed multi-category features like PaymentMethod and Contract into dummy variables.
Skewness Correction: Applied a Square Root Transformation to TotalCharges to normalise its distribution.
Feature Scaling: Applied Min-Max Scaling to all numerical features to bring them into a range of [0, 1].
📈 Visualizations 
Included Univariate Analysis: Distribution of Tenure, Charges, and Churn status.
Bivariate Analysis: Churn vs. Contract Type, Internet Service, and Payment Methods.
Multivariate Analysis: Scatter plots showing the relationship between Tenure and Total Charges, coloured by Churn.
Correlation Heatmaps: Identifying relationships between numerical variables.
💻 Tech Stack: 
Language: Python; 
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn. 
