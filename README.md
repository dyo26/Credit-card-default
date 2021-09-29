# Credit-card-default
Predicting whether or not credit card payment will default

Business Problem:
In bank, credit card payment is something usual to customer.
But for bank, a default event can be a crucial moment, because that means, they will take serious measure to attain their asset(s).
Therefore, a default event prediction can be helpful.
Why? because bank can have early warning system, based on scientific approach, not by experience or intuition from someone / credit analyst for example.
I'm not saying that someone's intuition is bad, but better if human resource can be used to perform something else rather than to analyze massive data to predict the default event.
Then, Machine Learning can be a good answer to this problem.

Approach:
Default or not default next month will be classified as 0 (not default) or 1 (default)
Should have data from several months regarding credit card payment history.
This problem will be a classification problem.

Methods:
Using Extreme Gradient Boosted Trees as Classifier, I tried to classify the default prediction based on several features from data.
The model had 80% accuracy, and optimized using GridSearch
As plus points, I used AWS SageMaker to deploy this model too. (cloud computing)
