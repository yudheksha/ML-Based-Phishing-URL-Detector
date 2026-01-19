# ML-Based Phishing URL Detector

A machine learning project that detects whether a URL is phishing or legitimate using engineered URL and webpage-based features. The notebook loads the dataset, performs preprocessing, trains multiple classifiers, and compares results including ensemble methods.

## What this project does
- Loads and explores a phishing URL dataset (11,055 rows, 30+ features)
- Splits data into train and test sets and applies feature scaling
- Trains and evaluates multiple ML models
- Tests ensemble approaches (Voting and Stacking) for improved performance
- Reports Accuracy, Precision, Recall, and F1 Score

## Models used
- Logistic Regression
- Decision Tree
- Random Forest
- SVC
- Gradient Boosting
- Gaussian Naive Bayes
- Voting Classifier (hard and soft)
- Stacking Classifier

## Results (test set)
- Decision Tree accuracy: 0.8705
- Random Forest accuracy: 0.9068
- Voting (hard) accuracy: 0.9051
- Voting (soft) accuracy: 0.9068
- Stacking accuracy: 0.9169 (best)

## Files in this repo
- `project_main_v2.ipynb` - end-to-end notebook (data prep, training, evaluation)
- `dataset_phishing 2.csv` - dataset used for training/testing
- `Data_Mining__Final_Report.pdf` - project report

## How to run
1. Open `project_main_v2.ipynb` in Jupyter Notebook or Google Colab
2. Keep `dataset_phishing 2.csv` in the same folder (or update the file path in the notebook)
3. Run all cells to reproduce training and evaluation

