# Exploration-of-Avito-Demand-Prediction

Avito, Russia’s largest classified advertisements website, is challenging us to predict demand for an online advertisement based on its full description
(title, description, images, etc.), its context (geographically where it was posted, similar ads already posted) and historical demand for similar
ads in similar contexts. With this information, Avito can inform sellers on how to best optimize their listing and provide some indication of how much interest they should realistically
expect to receive. In this report, we tried to improve the demand prediction performance by exploring the dataset and training various regression
models. We investigated the dataset by examining seven different hypotheses corresponding to the demand and extract new features for demand prediction. With the existed
and newly extracted features, we optimized six different regression method including Linear Regression, Random Forest, Support Vector Regression
(SVR), Gradient Boosting Regressor, LightGBM and XGboost to predict the demand. The performance of the prediction is evaluated
on root mean square error of predicted price for test dataset.
