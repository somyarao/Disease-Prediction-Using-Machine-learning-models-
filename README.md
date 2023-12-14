## Introduction 
In this project, I will walk through the Disease Prediction problem using Machine learning. The dataset used contains information about the diagnosis of heart disease patients. I will train machine learning models to predict whether a person has heart disease or not given the features such as chest pain type, age, sex etc.

## About the dataset
The dataset I have used for this project is the "Cleveland Heart Disease Data" from the UCI Machine Learning Repository. It comprises data on 303 individuals diagnosed with heart disease, categorized into five levels of severity. The dataset includes 14 variables, providing a comprehensive view of each patient's health status.

## Models Build and Reasoning 
### SVM
SVMs are powerful for datasets with complex but subtle relationships among the variables due to their ability to model non-linear boundaries. The heart disease prediction might benefit from the SVM's capability to use kernel functions to handle this complexity.

### Naive Bayes
Naive Bayes classifiers work well with categorical input variables. As there are several categorical variables in the dataset, such as chest pain type, fasting blood sugar, and resting electrocardiographic results, Naive Bayes can be a strong baseline model for this classification task.

### Logistic Regression
Logistic regression is well-suited for binary classification problems. Since the dataset involves classifying individuals into different levels of heart disease, this model can estimate the probability of the presence or absence of heart disease based on the input variables.

### Desicion Trees
Decision trees are useful for handling both continuous and categorical variables. The dataset includes a mix of these types of data, and decision trees can capture the non-linear relationships between the features and the target variable.

### Random Forest
Random forests are an ensemble learning method that can improve the predictive accuracy and control over-fitting, which can be a problem with decision trees. Given that the dataset has a moderate size (303 observations), random forests can capture complex interaction structures without the risk of overfitting associated with a single decision tree.

## Model Performance 
Each model was evaluated using performance metrics like accuracy, precision, recall, F1-score, and receiver operating characteristic (ROC) curves. This helped in gauging their effectiveness in correctly predicting heart disease presence based on the given attributes.

## Ensemble Model Building and Performance 
The ensemble model showcases strong performance with an accuracy of 86.44%. It maintains a balanced precision of 85.29% and recall of 90.62%, signifying its ability to make accurate positive predictions while effectively capturing a significant portion of actual positives. The F1 Score of 87.88% underscores its har- monized precision and recall, while the AUC value of 0.861 indicates its robust discriminatory power in distinguishing between the classes. This ensemble method amalgamates the strengths of individual models, resulting in a well-performing predictive model for Heart disease.

## Conclusion
The ensemble model emerged as a standout, showcasing its prowess with an impressive accuracy of 86.44%. This fusion of diverse models not only achieved a commendable accuracy but also displayed balanced precision and recall, affirming its ability to make precise positive predictions while effectively capturing a substantial portion of actual positives. With an F1 Score of 87.88% and an AUC value of 0.861, the ensemble method un- derscored its harmonized precision-recall balance and robust discriminatory power in distinguishing between various heart disease classes.
Comparatively, the Random Forest model stood strong with an accuracy of 84.75%, demonstrating high sensitivity and good specificity. Its robust F1 Score of 86.57% and an impressive AUC value of 0.914 portrayed significant discriminatory abilities, almost akin to the ensemble approach.
Further exploration into specific models revealed the Logistic Regression’s accuracy matching the ensemble at 86.44%, showcasing balanced precision and recall. Additionally, the Naive Bayes model demonstrated respectable performance with strong discriminatory power.
In juxtaposing the Random Forest and SVM models, both exhibited impressive accuracies and robust per- formances. The Random Forest model slightly outperformed in sensitivity and specificity, yet the SVM closely followed suit, portraying balanced precision-recall rates and competitive performance in pivotal pre- dictive metrics. This comparative analysis accentuates the nuanced strengths and competitive nature of these models in accurately predicting heart disease.
