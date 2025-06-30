# ML-Logistic-Regression

Data:Framingham Heart Study

Objective:

Predict the 10-year risk of Coronary Heart Disease (CHD) using logistic regression. By loading a dataset related to Framingham Heart Study, exploring the data, handling missing values, and building a logistic regression model are done to classify individuals based on their risk factors.

Results:

The results obtained from the Logistic Regression model so far are:

    Training Accuracy: 0.8540
    
    Testing Accuracy: 0.8573
    
The classification report for the testing set shows:

    For class 0 (No CHD): Precision of 0.86, Recall of 0.99, and F1-score of 0.92.

    For class 1 (10-Year CHD): Precision of 0.60, Recall of 0.07, and F1-score of 0.13.
    
The confusion matrix also provides a visual representation of the model's predictions versus the actual values on the test set.

These results indicate that the model is performing well in identifying individuals who do not have a 10-year risk of CHD (high recall for class 0), but it is not very effective at identifying individuals who do have a 10-year risk (low recall for class 1).


