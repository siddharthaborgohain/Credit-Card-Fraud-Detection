**Introduction:**

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.


In this project, I will analyse customer-level data that has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group. 

Key components involve data preprocessing, feature engineering, model selection, and evaluation metrics.

Ultimately, the project aims to provide a robust, efficient, and adaptive solution to safeguard financial transactions from the evolving landscape of fraudulent activities.


**Project Understanding**

Suppose you get a call from your bank, and the customer care executive informs you that your card is about to expire in a week. Immediately, you check your card details and realise that it will expire in the next eight days. Now, to renew your membership, the executive asks you to verify a few details such as your credit card number, the expiry date and the CVV number. Will you share these details with the executive?
In such situations, you need to be careful because the details that you might share with them could grant them unhindered access to your credit card account.
Although digital transactions in India registered a 51% growth in 2018–2019, their safety remains a concern. Fraudulent activities have increased severalfold, with approximately 52,304 cases of credit/debit card fraud reported in FY 2019 alone. Owing to this steep increase in banking frauds, it is the need of the hour to detect these fraudulent transactions in time to help consumers and banks that are losing their credit worth each day. Machine learning can play a vital role in detecting fraudulent transactions.
So far, you have learnt about the different types of machine learning models. Now, you will learn which model to choose for your purpose and the reason for it. Understanding models based on different scenarios is an important skill that a data scientist / machine learning engineer should possess. In addition, tuning your model is equally important to get the best fit for your given data.
By the end of this module, you will learn how you can build a machine learning model that is capable of detecting fraudulent transactions. You will also learn how to handle class imbalances present in any data set, along with model selection and hyperparameter tuning.


**Business problem overview**

For many banks, protecting customers’ profitability is one of the main business goals. However, bank fraud poses a threat to the brand of different banks. This situation is a situation that worries both banks and consumers as it causes a loss of financial importance, trust and confidence.
A Nielsen report estimates that global banking fraud will reach $30 billion by 2020. With the rise of digital payments, the number of frauds has also increased exponentially in new and different ways.
In the banking industry, using machine learning for credit card fraud is not only a trend, but also important for fraud monitoring and prevention. Machine learning is helping these institutions reduce manual review time, chargebacks and fees, and reject legitimate transactions.


**Understanding and defining fraud**

Credit card fraud is any dishonest act or behaviour to obtain information without proper authorisation from the account holder for financial gain. Among different ways of committing frauds, skimming is the most common one, which is a way of duplicating information that is located on the magnetic strip of the card. Apart from this, following are the other ways:

-Manipulation/alteration of genuine cards
-Creation of counterfeit cards
-Stealing/loss of credit cards
-Fraudulent telemarketing


**Data dictionary**

This data includes credit card transactions made by European cardholders for two days in September 2013. This data is suspicious and a good group (fraud) account accounts for 0.172% of the total stock. The dataset is also modified with principal component analysis (PCA) to protect privacy. Except for "Time" and "Value", all other features (V1, V2, V3, up to V28) are principal components using PCA. The special "time" contains the number of seconds between the first change in the configuration file and the next change. The "financial" property is the exchange rate. The unique "class" represents the class record, which has a value of 1 in the case of fraud and 0 otherwise.

**Project pipeline**

The project process can be summarized in the following four steps:

**Understanding the Data:** Here you need to load the data and understand the features available in it. This will help you select the features you need for your final design.

**Data Analysis (EDA):** Usually in this step, you perform univariate and bivariate analysis of the data and then perform feature transformations as required. Since Gaussian variables are used for the current data, there is no need for Z scaling. However, you can check if there is any distortion in the material and try to reduce it as it will create problems in the design process.

**Training/Testing Split:** Now that you know the training/testing split, you can do this to check the performance of your model using invisible data. Here k-fold cross validation method can be used for validation. You should choose a suitable value of k so that the minority is represented in the fold test.

**Building Model/Tuning Hyperparameters:** This is the final step where you can test different models and tune their hyperparameters until you get a certain level of performance on the given data. You should try different sampling methods to see if you can get a better model.

**Standard Test:** Test the standard using appropriate measuring instruments. Remember that since information is not equal, it is more important to identify a fraudulent transaction than a non-fraudulent transaction. Select appropriate measurements that reflect this business objective.

