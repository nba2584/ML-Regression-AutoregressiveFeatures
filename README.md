This project aims at improving the prediction accuracy of appliance energy usage in residential set-tings by exploring and comparing various regression and neural network models. 
Utilizing a dataset that includes energy consumption data from wireless sensors alongside at-mospheric temperature and pressure readings, this study aimed to predict energy usage 10 minutes in advance. 
To achieve this, the study focused on four regression models—multiple line-ar regression, support vector regressor, gradient boosting regressor, and random forest and three neural network/deep learning models—feedforward, long short-term memory (LSTM), and gated recurrent unit (GRU) for performance comparison. 
In this study traditional time lag auto-regressive features are manually created to capture short-term energy patterns even though modern time series forecasting models are available. 
Additionally, dimensionality reduction technique - principal component analysis (PCA) has been implemented to manage high-dimensional data, improve model performance, mitigate overfitting, and enhance both efficiency and interpretability. 
Feature importance through SHAP values were used to identify the most rel-evant factors influencing appliance energy usage. 
By addressing these aspects, the project aimed to provide more accurate and actionable predictions for energy management.
