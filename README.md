# Credit Card Fraud Detection Using Machine Learning

## Models Used
- Logistic Regression
- K Nearest Neighbors

## Dataset
The dataset used for this project is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders.

## Processing
The dataset is highly imbalanced, with only 0.172% of the transactions being fraudulent. So I have used the same number of non fraudulent transactions as fraudulent transactions to balance the dataset. There are 492 fraudulent transactions and 492 non fraudulent transactions in the balanced dataset.

## Results
- **Logistic Regression**:
    - Accuracy: 0.9645
- **K Nearest Neighbors**:
    - Accuracy: 1.0

## Conclusion
Both models performed well, with K Nearest Neighbors achieving perfect accuracy on the balanced dataset. Also observed that for 3 neighbors, the error rate was the least. Model's performance would be better tested on a larger dataset with more fraudulent transactions.