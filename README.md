# Online Customer Intention Prediction Model
To build a predictive model, which shall decide whether the customer will buy or not, the dataset had a total collection of session visits made by clients on our online store. Revenue shall be the Response Variable and others are the Predictor/Independent Variables.

**Click** Link to view project : [<b>Online Customer Intention Prediction</b>](https://github.com/BlessingNehohwa/Online_Customer_Intention_Prediction/blob/main/Customer%20Intention%20Prediction%20Model.ipynb)

# Dataset
The dataset consists of data points belonging to 12,330 sessions of customer visits to the website, it was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.

# Conclusion
We took a case study, performed Data Visualizations, made clusters based on customer behaviors, built three predictive models: Random Forest classifier, Logistic classifier, and K-nearest neighbor, and immediately dropped KNN after it had the lowest accuracy score. Compared the performance of the two algorithms left, Logistic Regression and Random forest models using Confusion Matrix and ROC curve and also wrote the predictions from both the models into respective data-frames, so that the business decision makers can know the exact customers who will generate the revenue and who will not, by writing those prediction outputs into CSV files. I have failed to hit my evaluation metric of 95% and only managed 90.4% with the Random Forest model which is not very bad.








Reference Sahu, S., 2021. Analytics Vidhya. [Online] Available at: https://medium.com/analyticsvidhya/predictive-web-analytics-a-casestudy-f30feda45002   
