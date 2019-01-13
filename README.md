# demand-forcasting
# Problem Statement
The problem of Inventory Demand Forecasting is, for example, that a grocery store needs to forecast demand for perishable items. Purchasing too many will end up discarding valuable product. Purchasing too few will run out of stock. Numerous businesses face different flavors of the same basic problem, yet many of them use outdated or downright naive methods to tackle it (like spreadsheet guided, stock-boy adjusted guessing). The current project outlines a scientific approach for inventory demand forecasting using Machine Learning.
## The Value Add
There are two ways such a model can add value: 1) By reducing the amount of overstocked items and 2) By increasing the amount of understocked items.

In the case of grocery stores, overstocked perishable items result in a direct loss since expired perishable items must be discarded. Other retail companies face a different issue with overstocking. For example a clothing store that overstocks on winter coats will 1) reduce limited store space that could have been used to sell winter boots and 2) potentially result in having to sell the coats at a discount or loss come Spring to make space available for new items. These financial losses are harder to measure, but depending on the size of the business and quality of the existing inventory demand forecasting model, losses can be tens or hundreds of thousands of dollars annually.

Understocking items is potentially a more severe issue. Understocking milk in a grocery store is likely to drive customers to a competitor. Losing a customer can cost hundreds if not thousands of dollars. Similarly, understaffing a restaurant on a busy day can result in long wait times and poor service, which would also result in loss of customers. Estimating the financial losses from understocking can be difficult since it’s not clear how much product would have been sold if the product were available. It’s even less clear how much customer value is lost since understocking drives customers away from a business. Nonetheless, it’s worth analyzing the frequency by which products run out of stock and attempting to estimate the financial loss of such occurrences.

# Project outline
## Data 

## Evaluation Metric
RMSE- Lower values are better, and the metric measures the ratio of predicted-to-actual values. 
## Validation Framework
use previous data to predict the upcoming events. i.e.,
Train a model using only data known as of 2016-12-31. Predict the sales for items in the range [2017-01-01 through 2017–01-14]. Measure the performance, P1
Train a model using only data known as of 2017-01-14. Predict the sales for items in the range [2017-01-15 through 2017–01-29]. Measure the performance, P2
Train a model using only data known as of 2017-01-29. Predict the sales for items in the range [2017-01-30 through 2017–02-13]. Measure the performance, P3
Average the performance scores, PAverage=(P1,P2,P3)/3.

# Leaderboard
private 48/764
public 43/764
