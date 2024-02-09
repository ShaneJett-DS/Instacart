# Instacart Repurchase Analysis

### <b>Goal</b>: 
This project takes a look at Instacart customer shopping behavior. The goal is to identify what drives consumers to repurchase items so that a reccomendation system can be built to make "items you may like" suggestions on the app. 
### <b>Analysis</b>: 
I began by looking at the most popular items purchased and the aisles and departments most frequently purchased from. As a result of high dimensionality, categorical variables were turned into frequency counts to represent popularity and reduce dimensionality. After creating these new features, a decision tree classifier was created to determine behaviors most likely to lead to repurchases. The feature importance values from this tree indicated that only a few variables were contributing to the majority of variance. As a result, a Principle Component Analysis was performed to determine which variables to eliminate. The day of the week variables were completely useless and thus eliminated during subsequent analyses. The subset of variables was then run through a decision tree model again to see if the results changed.
### <b>Conclusion</b>: 
I found that <b>93% of customers repurchased at least one item</b>. This means that many customers can benifit from a reccommendation system if we can determine what leads to these repurchases. <b>64% of the customers that ordered from the app more than 13 times from the app reordered items.</b> When that group of customers is makeing purchases from a moderately popular aisle, 72% of them repurchase that item. In short, customers that use the app frequently to purchase from popular aisles tend to be making a repurchase. 
Customer shopping behavior analysis.
