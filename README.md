# Credit_Risk_Classification

CREDIT ANALYSIS REPORT

Analysis Overview
The purpose of this analysis is to identify the most accurate indicator of model performance, which can be utilized by loan companies. Two distinct models were created: one fitted with the original data, and the other fitted with resampled training data. The train_test_split function was employed to evaluate the model's performance using training and testing datasets. The value counts of the original data show that 75,036 borrowers remain in good standing, while 2,500 borrowers are at risk. 

Results
The accuracy scores improved from 0.94 in the first model (using original data) to 0.99 in the second model (with oversampled data). Both models perform well in predicting healthy loans (class 0), but perform relatively poorly with high-risk loans (class 1). Notably, the second model's classification report indicates improved performance for high-risk loans due to oversampling.

Summary
Second model fitted with oversampled data displays considerable increase in accuracy as well as overall increase in  precision, recall, and F1-score compared to the first model. The second model is the best predictor of loan risk and can prove useful to loan companies.  
