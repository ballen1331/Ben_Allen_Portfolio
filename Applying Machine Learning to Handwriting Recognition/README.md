# Handwriting Recognition in R 

## kNN, SVM, and Random Forest Modeling Comparisons

## Project completed as class assignment for IST 707 (Applied Machine Learning)

### A few notes about the project:

• CSVs (digit_train and digit_test) with 4198 observations of 785 instances were used to test handwriting recognition accuracy using 'pixel' attributes of handwriting samples

• Using applicable packages in R, these models produced accuracies of .9212 for kNN, .9026 for SVM, and .9266 for Random Forest all tested with 10 repetitions of 5 fold cross-validation

• Based on the accuracy results and runtime, the Random Forest option performed best in predicting this type of pixelated handwriting data

• In the future, I would test against neural network and XBboosted models to detect any other complex / non-linear relationships


