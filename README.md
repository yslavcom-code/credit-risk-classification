Based on the Start Code coming with this assignment, a risk analysis was conducted using

These are results obtained

Healthy loans (class 0): 
        -near perfect precision (1 => correct 100%), 
        -recall 0.99 => correctly identified 99% of the 0 labels, hence 1% of healthy oans where wrongly qaulified as high risk
        -f1 score = 1.0 => harmonic mean of precision and recall is good
        -support - 22515 instances of class 0 in the test
High risk loans (class 1): 
        -precision 0.85 => predicting 1, it is correct in 85% cases => needs to be improved
        -recall 0.94 => correctly identified 94% of the high risk cases
        -f1 score = 0.89 => strong balance between precision & recall
        -support - 746 instances of class 1 in the test set

Note, the sets where split in the following fashion
X_train, X_test, y_train, y_test = train_test_split(x, y, test_size=0.3, random_state=1)

Perhaps, changing test_size could have a somewhat impact on overall results.