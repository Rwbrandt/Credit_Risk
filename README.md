# Credit Risk Prediction

## Ensemble Analysis
Analyzing and predicting the data using ensemble methods (Balanced Random Forest Classifier and Easy Ensemble Classifier) produced overall similar results.  Each of the results listed below were within at most .05 of each other, barely edging each other out in various confidence metrics.  Full results listed below

## Final Numbers:

### Which model had the best balanced accuracy score?
The Easy Ensemble Classifier has the better Balanced Accuracy Score of .728 compared to the Balanced Random Forest Classifier of .702

### Which model had the best recall score?
The Balanced Random Forest Classifier has the better recall score of 0.81, a full .05 better than the Easy Ensemble Classifier recall of 0.76

### Which model had the best geometric mean score?
The Easy Ensemble Classifier has the better geometric mean score of 0.73 compared to the Balanced Random Forest Classifier geometric mean score of 0.69

### What are the top three features?
The top three features are total_rec_int, last_pymnt_amnt, and total_pymnt_inv. All of these features come in with an importance score of over .06

------- 

## Resampling analysis
Predicting credit risks proved more confident than the prior Ensemble methods, producing results that were all in the mid to high 90's rather than the mid 70's.  The overall best performing method was the Naive Random Oversampling method, which had three metrics (precision, recall, f1) all coming in with a .99 result!  Full results listed below.

## Final Numbers:

### Which model had the best balanced accuracy score?
The best balanced accuracy score belongs to both the Logistic Regression and Naive Random Oversampling models, both coming in at .952

### Which model had the best recall score?
Simple Logistic Regression, Naive Random Oversampling each had a recall score of 0.99

### Which model had the best geometric mean score?
SMOTE, Simple Logistic Regression, and Naive Random Oversampling all had a geometric mean score of 0.95