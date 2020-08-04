## Telecom_Churn_Analysis_Prediction
Predict customer attrition with 80% accuracy for this dataset found on Kaggle. 

Data found on Kaggle at https://www.kaggle.com/blastchar/telco-customer-churn

----

# File 1: Telecom Churn Prediction

Exploration:
- Exploratory visualization to find distribution and significance of certain feautures
  - Histograms, barplots, heatmaps

Data Cleaning/Prep:
- Remove and impute null values in our data
- Encode categorical features
- Apply standard scaler to data

Model Selection:
- Cross validate different classifiers to select which model we will tune
  - Logistic Regression, SVM, Random Forest, K-Neighbors, Gradient Boosting Classifier
- Use grid search to tune the learning rate and depth of GB Classifier
- Further improve by applying SelectKBest and Chi2 to select best features

Model Evaluation:

- Evaluate model with confusion matrix and log-loss

Results:
- 80% accuracy, no churn (precision: 0.84, recall: 0.91), churn (precision: 0.68, recall: 0.51)
- Logloss: 0.401

# File 2: Telecom Viz

Visualize the distribution of customers across all features in the data frame. 
- hists, boxplots, barplots
