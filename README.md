# Predicting Customers Churn

Idea from [Yhat](http://blog.yhat.com/posts/predicting-customer-churn-with-sklearn.html), then modified by Hassen Taidirt to include business considerations.

***

In this notebook, I'll try to predict customers churn, in a business perspective to reduce churn costs. I started with this blog post from [Yhat](http://blog.yhat.com/posts/predicting-customer-churn-with-sklearn.html) then I modified their study because they didn't included business considerations in their predictions.

The goal is not only to predict which customer is more likely to churn. _Why_ do we want to predict customers churn? To reduce loss. Here, there is an implicit business goal. The predictive model doesn'r only need to preduct customers at risk but also reduce the company loss due to churns. That's what I do in this notebook, which is not covered in the original Yhat blog post (in fact, there is a mention of this business perspective, but no additional details were provided).

I will load a customers database of a telecom company and preprocess it before study. Then, I will discuss some modeling considerations that are specific to this database. Next, I will build few models and tweak them to find the best predictor that reduces costs. Finally, a conclusion that will also summarize learned lessons will close this notebook.

Here we go!

***

[https://github.com/htaidirt/predicting-customer-churn/blob/master/Predicting%20Customers%20Churn.ipynb](https://github.com/htaidirt/predicting-customer-churn/blob/master/Predicting%20Customers%20Churn.ipynb)