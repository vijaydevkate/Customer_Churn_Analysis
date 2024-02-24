## _Churn Prediction for Prepaid Phone Customers : Analyzing Prepaid Phone Data to Enhance Customer Retention for Phone Company_


### **Business Case**

* Customer Churn has a significant effect on a company's revenue.

* Customer acquisition is thought to be five times more expensive than customer retention.

* According to a study conducted by Bain & Company, a 5% increase in customer retention can result in a 25% to 95% increase in profits.


### **Problem Statement**


* The Phone Company aims to identify the customers who would discontinue service in September 2013 based on the prepaid phone data from the months of June, July, and August 2013.

* Using the dataset provided, classification models must be built that can categorize customers as 1s (likely to drop) or 0s (likely to stay or unlikely to drop).

* Understanding the traits of customers who are likely to drop the service allows the company to modify its services in order to improve customer retention rates.




### **Summary of Dataset**

#### **Initial Dataset**

* No. of Variables / Columns : 190
* No. of Rows / Observations : 66469
* No. of Missing Values : 8813
* No. of Categorical Predictors : 18
* No. Continuous Predictors : 171
* Number of 1s in Dataset : 13907
* Number of 0s in Dataset : 52562


#### **Final Dataset (for modeling)**

* No. of Variables / Columns : 85
* No. of Rows / Observations : 57656
* No. of Missing Values : 0
* No. of Categorical Predictors : 15
* No. Continuous Predictors : 69
* Number of 1s in Dataset : 7806
* Number of 0s in Dataset : 49850



### **Observations**



**_1) Higher the number of outgoing calls (last month), lower the chances for the customer to drop the service._**

<img width="309" alt="image" src="https://user-images.githubusercontent.com/70052374/225522286-0d5c8f4d-562d-4a44-9051-c80ec38a89ba.png">






**_2) Higher the duration for which a customer is inactive, higher the chances for the customer to drop the service._**


<img width="315" alt="image" src="https://user-images.githubusercontent.com/70052374/225518899-32cf99b5-a8db-45e7-9eab-f9800e8c6931.png">






**_3) Higher the number of recharges done by the customer, lower the chances for the customer to drop out._**


<img width="310" alt="image" src="https://user-images.githubusercontent.com/70052374/225519459-511785b6-b904-4eec-ae45-0ccd4ac24d29.png">




### **Recommendations**

* **_To summarize customer behavior, we can say that lesser engagement or higher period of inactivity from a customer increases the chance for them to drop the service._**

* **_The best thing the phone company can do to improve customer retention is to reduce the period of inactivity by introducing attractive packages that offer best plans for both incoming & outgoing , thereby encouraging more recharges & hence, more activity._**


