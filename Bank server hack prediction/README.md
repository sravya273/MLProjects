## Predict if the bank server will be hacked

#### Problem Statement  
All the countries across the globe have adapted to means of digital payments. And with the increased volume of digital payments, hacking has become a pretty common event wherein the hacker can try to hack your details just with your phone number linked to your bank account. However, there is data with some anonymized variables based on which one can predict that the hack is going to happen.  

Your work is to build a predictive model which can identify a pattern in these variables and suggest that a hack is going to happen so that the cyber security team can somehow stop it before it actually happens.  You have to predict the column 'MALICIOUS_OFFENSE'  

##### Data:  
INCIDENT_ID : Unique identifier for any incident log   
DATE : Date wof incident occurence  
X_1 to X_15 : Anonymized logging parameters  
MULTIPLE_OFFENSE : Target which indicates if the incident was a hack. 1: Yes 2: No   

##### Dataset:  
Train.csv: Training the data [23856*18] to be used for training the model.  
Test.csv: [15903*17] on which the predictions need to be made.   
