# Credit-Card-Fraud-Detection---ML-Classification-Algorithm---Python
The goal of this project is to build a machine learning model that can detect fraudulent credit card transactions based on the transaction data.

Data:

The dataset we will use for this project is the Credit Card Fraud Detection Dataset from Kaggle. The dataset consists of over 280,000 credit card transactions, including both fraudulent and non-fraudulent transactions. Each transaction has 30 features, including:

Time: Number of seconds elapsed between this transaction and the first transaction in the dataset
V1-V28: Anonymous features obtained through PCA transformation for confidentiality purposes
Amount: Transaction amount
Class: Binary variable indicating whether the transaction is fraudulent (1) or non-fraudulent (0)


Steps:

1. Load the Credit Card Fraud Detection Dataset (available at: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and explore the data to gain insights and visualize the data.
2. Preprocess the data by handling missing values, oversampling the dataset to deal with imbalanced classification and splitting the data into training and testing sets.
3. Build and train a Logistic Regression model.
4. Evaluate the performance of the model using appropriate evaluation metrics, such as accuracy, precision, recall, and F1 score.
5. Test the final model on the testing set and report its performance.
