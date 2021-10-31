# Insurance-Claim
It is an Hospital Insurance project dealing with insurance claim.
The business objective was to check if an health insurance claim was genuine or fraudulent . Pre processing techniques such as EDA , feature selection, outlier detection were carried out to clean the data. Various visualizations were also seen using seaborn,pandas proffiling and the less important features were dropped upon carrying out feature selection technique like decision tree classifier where the feature importance was plotted. The dataset was also checked if it was balanced or not and it was found to be imbalanced so in order to fix this over sampling by smote was implemented to fix it. A classification model was built by splitting the dataset into test and train dataset and finding the right hyper parameters to Random forest classifier, Decision tree with Ada boost and XG boost were found using grid search cv and then the accuracy of the models were found.The accuracy for Random Forest was 82.4 % for test and 82.34 % for train dataset , Decision tree  was 84.5 % for train and 82.5% for test dataset , with XG boost it was 86% for train and 83.6 & for test dataset , the models were deployed using streamlit which predicted if a given case was genuine or fradulent.

For Pre processing techniques such as EDA , feature selection, outlier detection ,Project Workflow  = Insurance Claim Project.pdf
For Model Building=
For Deployment=
Heroku Deployment link = https://insurance-claim-api.herokuapp.com/
