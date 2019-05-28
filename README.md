This is an exercise to explore college scorecard dataset using unsupervised learning techniques: association rule

Different from surpervised learnings, unsupervised learnings do not label data or have observed outcomes. Instead it explores 
hidden structures in data to identify grouping or labels for predictive analysis and association rule is one of the most common techniques 

Association rule is an expression of a relationship or association in the data. They taks the form "X implies Y"

In order to identify the underlying associations/relationships, we need some measure of significance. Below are the three most common way to construct and filter assiciation rules:

1. Support: the proportion of transactions that contain the itemset

2. Confidence: the proportion of transactions in terms of rules. p(Y|X)

3. Lift: the deviation in the support of the rule from the support expected under the assumption of independenceof the left and right hand sides. The greater the lift, the stronger the association. A lift of 1 indicates the itemsets are independent.

When association rules are constructed, they must satisfy both minimal support and confidence thresholds, however even with these requirements we’re often left with a long list of candidate rules. We can further reduce the pool of rules using the lift metric.
