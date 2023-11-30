# Market-Basket-Analysis

This dataset has 38765 rows of the purchase orders of people from the grocery stores.
We used Apriori algorithm to perform analysis. It is an algorithm for frequent itemset mining and association rule learning over relational databases.
We used The Apriori algorithm from the mlxtend library. For more datails check: https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/ and https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/#example-4-pruning-association-rules

Insights:
Based on the results from implementing association rules, we can see that "frankfurter" and "Vegetables" have the highest zhangs_metric value, and therefore the highest association of any two items. With a combined support of 0.042, it means both items were purchased together in 4.2% of all transactions.
The second association rule would be the "sausage" and "yogurt" with a zhangs_metric of 0.1.
