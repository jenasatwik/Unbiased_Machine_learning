The code is structured in the following way:

Data processing - In this section the basisc statistics and dimensions of the data are obtained. Further the data is cleaned and transformed in a way it is usable.

A module to train the data using specific hyperparameters: This module is designed to run the scikit package modules for each of the machine learning models. It also loops thorugh various shyperamater settings to find the set of hyperparameter that have best accuracy vs fairness metrics tradeoff.

A module to calculate the accuracy and fairness metrics of the models : This module is designed to calculate the four fairness mterics such as demograohic parity, Predictive parity, equalised odds and mutual information. This module is used in the mdoel training modules to find out the nest settings.

A module to store in microsoft excel and display the results : This module helps to store the accuracy and fairness results for all loops and exposrt into excel for furtjer analysis.

Statistical tests - These modules are used to perform the hypotheses testing using Wilcoxon signed-rank test and Levene's test
