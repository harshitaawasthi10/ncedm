# ncedm

1. Preprocessing Steps:

Dropped irrelevant columns: Customer ID, Purchase Date, Customer Name

Encoded categorical variables with one-hot encoding

Applied z-score anomaly detection to filter out outliers (z > 3)

Scaled numerical features using StandardScaler

2. Modeling:

Built a Logistic Regression model to predict Returns

Evaluated the model using accuracy and classification metrics

3. Z-Score Effect:

Z-score filtering helped reduce noise/outliers and hence boost model performance

4. Comparison

Compared the results with different models such as Random Forest, Decision Tree and Pruned Decision tree.
