
<h1>Logistic Regression on Titanic Dataset</h1>
<h2>Project Overview</h2>
<b>This project applies Logistic Regression to predict the survival of passengers on the Titanic using the famous Titanic dataset. The model was built by carefully cleaning the data, selecting relevant features, and optimizing its performance through trial-and-error methods including regularization techniques and validation methods.</b>

<h2>Steps Involved</h2>
<b><u>1. Data Cleaning</u></b>
Handled missing values, standardized the data, and ensured all necessary columns were in appropriate formats.
Key Tasks:
Treating null values in columns like Age, Fare, and Embarked.
Dealing with outliers using box plots and statistical techniques.
2. Data Preprocessing
Label Encoding was used for categorical variables (e.g., Sex, Embarked).
Standardized numerical features to ensure the logistic regression model can make accurate predictions.
3. Feature Selection
Selected important features like Pclass, Sex, Age, SibSp, Parch, Fare, and Embarked.
Performed multicollinearity checks using VIF (Variance Inflation Factor) to identify and remove highly correlated variables.
4. Correlation Checking
Analyzed the correlation between features using heatmaps and correlation matrices to ensure that no redundant features were included in the model.
5. Treating Null Values and Outliers
Imputed missing data in key columns (Age, Fare), replacing outliers where necessary.
6. Model Building
Implemented Logistic Regression to model survival predictions.
7. Model Evaluation
Cutoff Threshold Adjustment: Implemented a cutoff of 0.4 instead of the default 0.5 to optimize for better recall and F1 score.
Evaluated performance using:
F1 Score
Recall Score
ROC Curve to assess the model’s performance across different thresholds.
8. Regularization
Applied L1 Regularization (Lasso) to prevent overfitting and improve the model's generalization ability.
Tuned the regularization strength through a trial-and-test approach to achieve the best performance.
9. Validation Methods
K-Fold Cross Validation was used to ensure the model performs well across different subsets of the data.
Train-Test Split was employed to partition the dataset for model training and testing.
10. Model Accuracy
The model’s accuracy was improved significantly through regularization and validation techniques, achieving an optimal balance between recall and precision.
11. Model Deployment
After training and validating the model, it was prepared for deployment, with the goal of accurately predicting passenger survival.
CHECK OUT MY CODE OVER HERE!:https://github.com/nabihacodes/TITANIC-SURVIVAL-PREDICTION--LOGISTIC-REGRESSION
