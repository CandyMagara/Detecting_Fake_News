# Detecting_Fake_News
Using python to detect fake news.

In this project I used machine learning algorithms to classify fake and valid news articles and statements.

The data used is obtained from the LIAR dataset. This dataset was developed by <a href='https://sites.cs.ucsb.edu/~william/papers/acl2017.pdfWilliam' target='_blank'> William Yang Wang </a> and consists of three files namely train, test and valid.  In the project I compare the performance of Passive Aggressive, Logistic Regression, Naive-bayes, Stochastic Gradient Decent, Random Forest and Linear SVC classifiers to determine the best classifier to build a fake news detection model. In this project hyperparameter tuning is done using GridSearchCV and RandomizedSearchCV. 

Finally, the classifier with the best performance is the Logistic Regression model.
