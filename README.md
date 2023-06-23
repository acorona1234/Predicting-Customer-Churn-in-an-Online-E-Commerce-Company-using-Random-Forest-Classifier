# Predicting-Customer-Churn-in-an-Online-E-Commerce-Company-using-Random-Forest-Classifier

### E-COMMERCE CHURN: DEVELOPED BY AMY CORONA 

#### In this workbook, we will explore ecommerce churn using EDA and Sklearn, resulting in a model that can predict churn with 90% accuracy!

#### If you like this workbook, please give it an upvote!

* [Data Preprocessing](#section-one)
* [Random Forrest Classifier (90% Accuracy!)](#section-two)
    - [Feature Importance (Tenure explains 47% of churn!)](#subsection-one)
    - [ROC Curve](#anything-you-like)
* [Conclusion](#section-three)

Introduction:
In today's competitive landscape, customer retention plays a crucial role in the success of any business. Recognizing the importance of identifying customers who are likely to churn, a leading online E-Commerce company has provided us with a dataset to develop a predictive model that can accurately forecast customer churn. The objective is to enable the company to proactively approach customers and offer targeted promotions to prevent churn.

Dataset Description:
The dataset we have at our disposal belongs to the aforementioned online E-Commerce company. It encompasses a range of customer attributes, including tenure, preferred login device, city tier, warehouse-to-home distance, preferred payment mode, gender, hours spent on the app, number of devices registered, preferred order category, satisfaction score, marital status, number of addresses, complaints, order amount hike from last year, coupon usage, order count, days since the last order, and cashback amount.

Methodology:
To tackle this predictive challenge, we have employed the Random Forest classifier, a powerful machine learning algorithm known for its ability to handle complex datasets and provide accurate predictions. By leveraging an ensemble of decision trees, Random Forest combines the strength of multiple models to achieve robust and reliable results.

<a id="section-one"></a>

### Data Preprocessing

#### This section will go over handling missing values as well as feature transformation

![image](https://github.com/acorona1234/Predicting-Customer-Churn-in-an-Online-E-Commerce-Company-using-Random-Forest-Classifier/assets/73566258/0ce3349b-e8cf-4567-811c-bac1816bb0fa)

![image](https://github.com/acorona1234/Predicting-Customer-Churn-in-an-Online-E-Commerce-Company-using-Random-Forest-Classifier/assets/73566258/6b96fb7a-724c-4990-9578-57feac965024)

<a id="section-two"></a>

## Random Forrest Classifier
### The Random Forest classifier demonstrates a prediction accuracy of over 90% in forecasting churn!

![image](https://github.com/acorona1234/Predicting-Customer-Churn-in-an-Online-E-Commerce-Company-using-Random-Forest-Classifier/assets/73566258/3e5fbb98-de8d-405d-9d4d-a21a260395df)

<a id="subsection-one"></a>

## Feature Importance

### Analyzing the importance of each feature will provide us with a comprehensive understanding. Notably, "Tenure" significantly contributes to churn, accounting for 46.67% of its explanation.

![image](https://github.com/acorona1234/Predicting-Customer-Churn-in-an-Online-E-Commerce-Company-using-Random-Forest-Classifier/assets/73566258/f79ef8a6-809b-4c58-932e-ce679f0c1b7e)

<a id="anything-you-like"></a>

## ROC curve

### Despite the use of alternative classifiers, the Random Forest classifier remains the most accurate. To visualize its performance, let's plot the Receiver Operating Characteristic (ROC) curve.

![image](https://github.com/acorona1234/Predicting-Customer-Churn-in-an-Online-E-Commerce-Company-using-Random-Forest-Classifier/assets/73566258/ef2a916e-4910-43c4-9265-ef08cc6aaf27)

<a id="section-three"></a>
## Conclusion

This project has focused on developing a Random Forest classifier to predict customer churn in the online E-Commerce industry. By analyzing a comprehensive dataset provided by a leading E-Commerce company, we aimed to identify the most influential features and create a model that can accurately forecast customer churn.

Our results have demonstrated a high level of accuracy, with the Random Forest classifier achieving a prediction accuracy of 90%. Additionally, we have identified the feature importance within the dataset, with the highest importance assigned to "Tenure" (46.67%). It is noteworthy that the remaining features collectively contribute to the prediction power, ensuring a comprehensive analysis.

The implications of our project are significant for the online E-Commerce company. By leveraging the predictive power of the Random Forest classifier, the company can proactively identify customers who are likely to churn and implement targeted strategies to retain them. This approach has the potential to increase customer loyalty, improve customer satisfaction, and boost overall business revenue.

In the future, further enhancements could be explored, such as feature engineering, hyperparameter tuning, and model optimization, to potentially improve the performance of the Random Forest classifier even further. Additionally, deploying the model in a production environment would enable real-time churn prediction and facilitate timely interventions by the company.

Ultimately, the successful application of the Random Forest classifier in predicting customer churn underscores the value of data-driven approaches in understanding and addressing customer behavior. By harnessing the power of machine learning and predictive analytics, businesses can proactively tackle customer churn and drive sustainable growth in today's dynamic marketplace.



