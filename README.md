# Data-Mining-255
Data set : Dataset : This dataset is a groceries data set bought by customers.



### Objective : Our aim is to find the frequent patterns using a minimum threshold using apriori and fpgrowth.


1. Installed the necessary libraries for association rules, apriori and fpgrowth.
2. Unnecessary columns are dropped.
3. One Hot Encoding is performed on the dataset.
4. Applied the apriori algorithm with min_support as 0.05
5. There were 30 frequent items with min_support>=0.05.
6. Applied association rules using the lift metric and min_threshold as 1.
7. Patterns 
```
38% of the transactions containing vegetables contain whole milk.

29% of transactions containing whole milk have vegetables.

22% of transactions containing whole milk have rolls/buns.

30% of transactions containing rolls/buns have whole milk.

40% of transactions containing yogurt have whole milk.

21% of transactions containing whole milk have yogurt.
```
8. Applied the fpgrowth algorithm with min_support as 0.05.
9. Applied the association rules with confidence as the metric and min_threshold as 0.1.
10. Patterns
```
40% of transactions containing yogurt have whole milk.

21% of transactions containing whole milk have yogurt.

38% of the transactions containing vegetables contain whole milk.

29% of transactions containing whole milk have vegetables.

22% of transactions containing whole milk have rolls/buns.
```

