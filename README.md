# Optimizing-variables-
The number and variables optimized through Regularization technique without affection model performance up to a threshold level.


About the dataset

The dataset selected for implementation of the proposed approach is- ‘MALWARE ANALYSIS DATASETS: TOP-1000 PE IMPORTS’. The dataset is contributed by Angelo Oliveira which is a part of his P.hD research. It contains 1000 imported functions extracted from ‘pe_imports’ of static analysis techniques.

The dataset contains 1929 benign program (good-ware) and 45651 malwares, 1000 PE imported functions. These 1000 features each have a binary class of being imported (1) or not (0).



The repository demonstrates how to reduce the number of variables through Ridge and Lasso Regression on a dataset of 1000 variables as features. We will thus also end up classifying the program as malware or goodware to comapre the perforamnces using the full range of variables(1000) and reduced number of variables.


Process:

Classification using 1000 features by Random Forest Classifier ----> Ridge Regression and Analysis ----> Selection of threshold level for eliminating variables with coefficients lower than the threshold ----> Random Forest Classifier for classification, but this time for each threshold level different number of features. ----> A graph of number of variables vs threshold level and another graph of F-1 score vs threshold level was thoroughly studied. Then upon optimization, consequently a threshold level was finally selected. Accordingly, the number of variables and the variables itself were updated.  


