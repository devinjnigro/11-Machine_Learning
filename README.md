# 11-Machine_Learning

##Credit Risk Resampling

In the resampling notebook, multiple models were used to train and test loan data to determine which model most effectively predicts whether the loan applicant is high risk or low risk. The Naive Random Oversampler was found to have the highest balanced accuracy score of 67.43%, while the SMOTE Oversampler had the best average recall score of 69%. The Naive Random Oversampler also had the highest geometric mean of 67%. Based on the above results, none of the models should be considered sufficiently accurate in order to determine a loan applicant's credit worthiness; however, if one model had to be chosen, it would be the Naive Random Oversampler.

##Credit Risk Ensemble

A Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier were trained in order to compare each algorithm's results. The AdaBoost Classifier had the highest balanced accuary score (93.2%), recall (94%) and geometric mean (93%), making it the most reliable classifier model. Based on the Random Forest Classifier, the top three features that contribute to the classifier's results are 1: total received principal (9.18%), 2: total_pymnt_inv (6.41%), and 3: total payment (5.76%).
