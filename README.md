# ADA442 (Statistical Learning) - Term Deposit Subscription Prediction Project

The objective of this project is to build a machine learning model to predict
whether a client of a bank will subscribe to a term deposit or not. The dataset includes a variety of customer-related data, including age, 
marital status, job, education level, and more. Building a reliable model to assess client interest 
in a term deposit is the project's main goal. After stages such as data cleaning and preprocessing, 
the most suitable model was selected. For this purpose, the examination of various techniques 
such as logistic regression, random forest classification, SVM, ridge classifier and XGBoost on 
a subset of 4119 randomly selected data from the bank marketing data set, which consists of 
41189 data, revealed prediction models that will allow predicting consumer behavior.

The data is related with direct marketing campaigns (phone calls) of a Portuguese
banking institution. The classification goal is to predict if the client will subscribe
a term deposit (variable y). The data is related with direct marketing campaigns
of a Portuguese banking institution. The marketing campaigns were based on
phone calls. Often, more than one contact to the same client was required, in
order to access if the product (bank term deposit) would be (‘yes’) or not (‘no’)
subscribed.

Used dataset: https://archive.ics.uci.edu/dataset/222/bank+marketing

We used StreamLit to deploy the 
model. When implementing the model on StreamLit, we did not implement the whole process. 
For instance, we did not include the hyperparameter tunings and other methods to determine 
which model is suitable because we have already analyzed the possible models, and 
implementing these processes would have slowed down the process. In contrast to adding these 
parts, we included the preprocessing

StreamLit Link: https://ada442-banking-project-ngjy4cxah8uhgsagcfdhbl.streamlit.app/

StreamLit Repository: https://github.com/burakkoc5/ada442-banking-project