# Display Advertising Challenge
(https://www.kaggle.com/c/criteo-display-ad-challenge/data)  

The data was no longer available at the speciefied link  

I was able to find it from Criteo.  
(http://labs.criteo.com/2014/02/kaggle-display-advertising-challenge-dataset/)  

I suspect it is not the exact data set used for the challenge because of the number, oder, name of the variables. It consists of more than 46M rows. I used random sampling to obtain 300000 rows of data. /with respect to my available resources/  

About the data  
Data fields  
Label - Target variable that indicates if an ad was clicked (1) or not (0).  
I1-I13 - A total of 13 columns of integer features (mostly count features).  
C1-C26 - A total of 26 columns of categorical features. The values of these features have been hashed onto 32 bits for anonymization purposes.   
The semantic of the features is undisclosed.  
 
When a value is missing, the field is empty.  

Until I know more about how to deal with the hashed values I would leave them out from the analysis. /"Hash functions may output the same value for different inputs" - To me that doesn't speak accuracy in the calculations. But as I said. I will pay attention to that later.    

I plan to use Logistic regression for this task.  
