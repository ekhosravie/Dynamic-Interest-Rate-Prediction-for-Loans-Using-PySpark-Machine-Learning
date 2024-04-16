Dynamic Loan Pricing with Spark Machine Learning
This repository demonstrates a Spark Machine Learning application for predicting loan interest rates based on customer and product characteristics.

Functionality:

Builds a Random Forest Regression model to predict interest rates.
Preprocesses categorical data using StringIndexer and OneHotEncoder.
Evaluates model performance using Root Mean Squared Error (RMSE).
Requirements:

Apache Spark
pyspark
Running the Code:

Clone this repository.
Ensure you have Spark installed and configured.
Run the script: spark-submit dynamic_loan_pricing.py (replace with your actual script name)
Note:

This code uses a small sample dataset for illustration purposes. Replace it with your actual data for real-world use cases.
Additional Considerations:

You can further enhance the code by:
Adding logic to classify predicted interest rates (e.g., 'High', 'Medium', 'Low').
Tuning the Random Forest model parameters for better performance.
Training and deploying the model in a production environment.
