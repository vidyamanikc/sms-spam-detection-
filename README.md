# sms-spam-detection-
pre-processing phase
*Tokenization  
*Lemmatization 
*Removal of Stop Word 
*Document Representation


The features that we have extracted and evaluated are as follows:-
Presence of Mathematical Symbols.
Presence of URLs
Presence of Dots
Presence of special symbols
Presence of emotions(emoji)
Lowercased words 
Uppercased words
Presences of Mobile Number
Keyword specific
Message Length

After extracting features, classification accuracy is being tested using machine learning classifiers: 
 Naïve Bayes
 Logistic Regression 
 Random Forest. 

After using machine learning classifiers, 
Naïve bayes accuracy score is  0.989237668161435
Logistic regression score is 0.9811659192825112
Random forest score is 0.967713004484305

conclusion
Among all the machine learning classifiers naïve bayes classifier is best for sms spam detection.
Using Naïve bayes classifier, it increases the accuracy of the system.
They are highly scalable.
It takes very less time to train the large data as compared to other classifier.
The error rate is very low.
It gives more accurate result than logistic regression, random forest.
