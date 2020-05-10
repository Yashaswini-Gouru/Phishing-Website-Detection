# Phishing-Website-Detection

Phishing Website Detection:
Over the years there have been many attacks of Phishing and many people have lost huge sums of money by becoming a victim of phishing attack. In a phishing attack emails are sent to user claiming to be a legitimate organization, where in the email asks user to enter information like name, telephone, bank account number important passwords etc. such emails direct the user to a website where in user enters these personal information. These websites also known as phishing website now steal the entered user information and carries out illegal transactions thus causing harm to the user.Phishing website and their mails are sent to millions of users daily and thus are still a big concern for cyber security.
A phishing website (sometimes called a "spoofed" site) tries to steal your account password or other confidential information by tricking you into believing you're on a legitimate website. You could even land on a phishing site by mistyping a URL (web address).

Project:
The aim of the project is to extract the features from the phishing URL's and Legitimate URL's and differentiate them.

The dataset has two text files one with Phishing Url's and the other with legitimate url's.
Extracting the features from the urls code is present in FeatureExtraction.ipynb file.
The Extracted features has vales 0,1,2.
Where Legitimate-0
      Phishing-1
      Suspicious-2
    
 The Extracted features are formed as Dataframes.
 The Models used for Prediction are:
   Decision Tree Classifier
   Random Forest Classifier
   Logistic Regression
   K-Nearest Neighbors Classifier
   Grid Search
   Neutral Networks
   
  The Accuracies ,Confusion matrix and False positive rates for all the models are obtained.
