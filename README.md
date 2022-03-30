# Data Mining & Machine Learning

## Hotel Reservation Cancellation prediction and Predictive Analytics of Airbnb

(The repository for the Data Mining & Machine Learning project.)
## Abstract

The travel and rental accommodation industry has seen a bloom in the past few decades and it has a major contribution in the economy of many countries
in the world. Reservation cancellation strongly impacts the demand management decision of any hotel and also
disturbs the accurate forecast of revenue. By having accurate forecast of cancellation from customers, hotels
can enhance the revenue management performance and improve the cancellation policies. The paper also intends to
build a uniform platform for Airbnb price estimation as per property characteristics, where both host and guest
can get idea of about the price dynamics of Airbnb market.

In project we have 3 datasets to address all the above problems. For booking cancellation we use Gaussian Naive Bayes, logistic regression, Decision tree, and Random Forest for classification. Random forest performs well on data with accuracy 88% and ROC score 0.957. For Airbnb datasets, we use Random Forest regression, Decision tree regression and Linear Regression for New York data and for London dataset, we use K-nearest neighbour Regressor and Extreme Gradient Boosting (XGBoost). The Random forest and XGBoost outperformed others with having R2 on unseen data 0.645 and 0.661 respectively.

Furthermore, this work aims to encourage other researchers to conduct research in this business problems and increase the prediction power and accuracy by embedding the other data mining techniques like natural language processing and text analysis of reviews and listing description texts.

The project is consisted of 3 parts 

1) Hotel Booking Cancellation prediction:
2) Price prediction of New York Airbnb Market
3) Price Prediction of London Airbnb Market

## Datasets
![image](https://user-images.githubusercontent.com/102433874/160916351-4d314a63-e471-44a9-bfe0-4acac32d8b75.png)

# Hotel Booking Cancellation prediction

![image](https://user-images.githubusercontent.com/102433874/160917278-3b6c50d8-3780-49b3-8214-e8445cfb1ce1.png)

![image](https://user-images.githubusercontent.com/102433874/160917462-6558cbfc-31ae-4982-a062-9733a9dba85f.png)

![image](https://user-images.githubusercontent.com/102433874/160917507-3d1b2054-0d44-4af2-8ae9-d7913ae68aa9.png)

![image](https://user-images.githubusercontent.com/102433874/160917560-2fc4cc42-5ea4-4b34-82fe-9265d2180f7b.png)

# Price prediction of London Airbnb Market

![image](https://user-images.githubusercontent.com/102433874/160917729-3a5648a6-f163-41f6-9f85-cd5a9488f957.png)

# CONCLUSION AND FUTURE WORK

1) Foreign customers are more cautious on canceling bookings when traveling in another country.
2) User should go for listing with less number of reviews with same characteristics because that might have less rental price
3) Future plan is to deploy the model on web-cloud (preferably PaaS) for Airbnb end users both host and guest where they can understand which features are more dominant in Airbnb market price and get a fair estimation of the rent
