
Task 3

Feature Engineering for Predictive Modeling

Background Information

In this task, focus on preparing the data for modeling and building your first predictive model. This includes splitting the dataset into training and test sets, encoding categorical variables, and scaling numerical features for consistency. After preprocessing, you will apply Logistic Regression, a classification algorithm, to predict flight cancellations. The model's performance will be evaluated using metrics such as accuracy, precision, and recall to assess its predictive capabilities. This stage is crucial for transforming raw data into actionable insights through predictive analytics.

Task Information

Split the Data: Divide your dataset into two groups:
Training Set: The data the model will learn from.
Test Set: The data we'll use later to see how well the model performs on unseen data.
Encode Categorical Variables: Change any text categories (like "Airline" or "Origin") into numbers that the model can use.
Feature Scaling: Make sure all the numerical features are on a similar scale (so one doesn't overpower the others).
Model Building (Logistic Regression):
Choose Logistic Regression as your algorithm.
Train your model using the training set.
Model Evaluation:
Use your trained model to make predictions on the test set.
Compare the predictions to the actual flight cancellations.
Calculate evaluation metrics (like accuracy, precision, and recall) to see how well your model did.
Resources

Pre-processing Data
Feature Engineering
What is feature Engineering


Hints

Use LabelEncoder or OneHotEncoder for categorical columns.
Use StandardScaler for feature scaling.
Use train_test_split to split data.
Use LogisticRegression() from sklearn for model building.
Evaluate using accuracy, precision, recall, F1-score.
