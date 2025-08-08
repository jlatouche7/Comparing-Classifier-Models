# Comparing-Classifier-Models

My goal is to find a model that can explain the success or failure of a marketing interaction. The effects of marketing efforts tend to be very difficult to quantify, so my goal is to identify which marketing efforts or traits of the customers led to the customer eventually subscribing. 

Here is a link to the jupyter notebook with my analysis: https://github.com/jlatouche7/Comparing-Classifier-Models/blob/ad7512d5f243061be87dc205bc7c16a932a8dfce/Bank%20Marketing.ipynb


I trained several different models, simple and finely tuned to see which ones would give me interpretable and accurate results that inform about what is making the difference between people subscribing and not subscribing. I trained several different classifier models to find a model that would best explain the marketing interactions. I landed on using the Logistic Regression model I built because of its accuracy, interpretability and efficicency. This model was able to correctly identify whether a customer would subscribe at a little over than a 90% rate. 

My model did identify a few things in particular that really correlated with if a consumer subscribed to the bank deposit or not:
	
	1. Method of Contact - Contacting customers via their cellular was much more effective than contacting customers via their landline/telephone. Going forward, I would recommend targeting customers that you have their cellular information.
2. Time of year - It seems that there are certain months that people are more likely to subscribe during. March especially should be a time to target. While September also seemed to lead to more success. While March and September were good months, June should be a month to avoid.

Overall I recommend putting a priority on obtaining customers cell phone number rather than home phones and doing flighted marketing campaigns that target the months of June and September in particular. I think implementing those two recommendations will improve the conversion percentage of subscriptions and help optimize your marketing budget.
