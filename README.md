# employee-attrition-prediction
Data Science Project on predicting Employee Attrition

### Learning Points

**Recursive Feature Elimination**
* Works by recursively removing variables, then building a model with remaining variables, 
makes use of model accuracy to identify which variable contribute most to the prediction of employee attrition.
* Greater the feature accuracy, more likely to remain in the dataset.

**Support Vector Machine**
* The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classifies the data points.

Explanation reference: https://towardsdatascience.com/support-vector-machine-introduction-to-machine-learning-algorithms-934a444fca47

**Fold Cross Validation**
* Cross-validation is a resampling procedure used to evaluate machine learning models on a limited data sample

Explanation reference: https://machinelearningmastery.com/k-fold-cross-validation/

**Classification Report**
* The classification report visualizer displays the precision, recall, F1, and support scores for the model.

Explanation reference:

https://medium.com/@kohlishivam5522/understanding-a-classification-report-for-your-machine-learning-model-88815e2ce397

https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html

**Variable Importance**
* Variable importance refers to how much a given model "uses" that variable to make accurate predictions. The more a model relies on a variable to make predictions, the more important it is for the model. It can apply to many different models, each using different metrics.
* If a variable has very little predictive power, shuffling may lead to a slight increase in accuracy due to random noise.
* Helps weed out certain predictors that are contributing to nothing and that instead add time to processing.
