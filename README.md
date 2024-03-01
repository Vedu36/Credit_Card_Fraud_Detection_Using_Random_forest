<h1>Credit Card Fraud Detection</h1>
<h2>Overview</h2>
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset comprises transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, with fraud transactions accounting for only 0.172% of all transactions.

<h2>Dataset Description</h2>
  
Source: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud]
Size: 284,807 transactions

<h2>Features:</h2>

Features V1-V28: Principal components obtained with PCA transformation

Time: Seconds elapsed between each transaction and the first transaction in the dataset

Amount: Transaction amount

Class: Response variable; 1 indicates fraud, 0 indicates legitimate transaction

<h2>Data Exploration</h2>

Conducted data exploration and preprocessing using Pandas, NumPy, Matplotlib, Seaborn.

Descriptive statistics rounded to 2 decimals and transposed for better readability.

Checked for missing values and duplicates.

<h2>Visualization</h2>

Visualized the distribution of transaction types using a count plot.

Analyzed correlation between features using a heatmap.

![image](https://github.com/Vedu36/Credit_Card_Fraud_Detection_Using_Random_forest/assets/118358451/96384087-a0d6-4412-a14a-a0b5ec5a2a55)

<h2>Data Preprocessing</h2>

Normalized the data by separating legitimate and fraudulent transactions.

Balanced the dataset by randomly sampling legitimate transactions to match the number of fraudulent transactions.

<h2>Model Training and Evaluation</h2>

Split the dataset into training and testing sets.

Trained a Random Forest Classifier on the training data.

Evaluated the model's performance using accuracy score and confusion matrix.

Achieved a testing data accuracy of 95.53%.

<h2>Technologies Used</h2>

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn
