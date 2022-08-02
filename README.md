About the assignemnt: An assignment given in Machine Learning Course. including preprocessing the data, applying different models in order to predict the 
"event primary" column, choosing the best parameters and evaluating the results. Finally, compare the different models - Random Forest and Logistic Regression.

**Main parts:**
1. Preprocessing the data - check Null values and remove them according to different methods, convert non-numeric features to numeric using dummy variables.
2. Split the data to train (80%) and test (20%)
3. Normalize the data and apply  Logistic Regression model using pipeline 
4. Use GridSearchCV in order to find the best paramters for the model (Tuning methods)
5. Model Evaluation - Compute accuray and check wether the model overfits
6. Apply Random Forest model, using tuning and selecting the best parameters for the model. Check the accuracy according to the number of estimator, check wether the model overfits and the effect of the batch size.
7. Who is the best model - check the best model using ROC curve methods - Compare the Random forest and the Logistic regression mods.
