# In-app-Purchase-Prediction

In-app purchase is a piece of content or feature being purchased inside of the app. Whether a user will
make an in-app purchase is a problem of high interest to mobile apps in general due to the direct impact
on the bottom line. The ability to predict the probability of users purchasing within a certain time window
in the future promises various benefits. An example is that marketers could better target their
communication to provide purchase incentives to the right group of users at the right time to boost
revenue for the app.

The problem we are solving is to predict the probability of in-app purchase for a 7-day and 14-day time
window of 312,568 ​ users​ of a particular app based on their past behaviors on the app and their
receptiveness of marketing communication from the app itself. We use Random Forest and XGBoost
algorithms to build predictive models, using features that are aggregated to user-level. The performance
of models is assessed using AUC as the performance metric. Our best model achieved a 0.9765 AUC
score. This paper discusses the details about the characteristics of the data, the features we extract, and
our model training process.
