# Phishing-data-analysis

Phishing is a type of cyber attack in which a perpetrator attempts to trick individuals into providing sensitive information, such as login credentials or financial information, by posing as a reputable entity in electronic communication, such as email or social media messages. 
The goal of a phishing attack is typically to steal personal information or money. Here is an example url and its elements :

https://www.example.com:443/path/to/file.html?param1=value1&param2=value2#fragment

The domain name : www.example.com 

Path:  "/path/to/"

The "file" : ”file.html" 

param: “?param1=value1&param2=value2” ( additional parameters )

# The dataset

The dataset contains 10 000 urls and 75 numerical features including 1 class feature ( 1 = phishing , 0 = normal ) 

# Analysis step and code 

At first, with the code in Python I've performed some pre-processing, an exploratory analysis and tested some machine learning models ( KNN Classifier, Decision Tree Classifier and Random Forest ) on different sets of features to determine which features are the most usefull to guess that an url is phishing.

# Presentation

The presentation of the project can be found here : https://docs.google.com/presentation/d/1M06Gd8PzId6Wh6xDnk3oV543sHFI8J_ZeWNEc8L_fug/edit?usp=sharing 
