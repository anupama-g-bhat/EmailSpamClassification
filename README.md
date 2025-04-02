# Email Spam Classification Using Logistic Regression
This project applies Logistic Regression to classify emails as spam or not spam based on a dataset.

## Dataset
  The dataset (`emails.csv`) contains email features and a `Prediction` column (1 = spam, 0 = not spam).
  Non-numeric columns are encoded using one-hot encoding.

## Steps
1. Load and preprocess the dataset.
2. Standardize numerical features using `StandardScaler`.
3. Train a Logistic Regression model.
4. Evaluate performance using accuracy, precision, recall, and F1-score.
5. Visualize results with a confusion matrix.

## Results
  Accuracy, precision, recall, and F1-score are displayed after model evaluation.

## Dependencies
  Python  
  Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn  
