## Problem Statement

Build the Apriori algorithm by first determining frequent itemsets and then proceeding to identify association rules. 
1. Implement both Fk-1 * F1 and Fk-1 * Fk-1 methods.
2. Enumerate the number of frequent closed itemsets as well as maximal frequent itemsets on each of your data sets for each of the minimum support thresholds. Compare those numbers with the numbers of frequent itemsets.
3. Implement confidence-based pruning to enumerate all association rules for a given set of frequent itemsets. Use the previous data sets, with three levels of support and three levels of confidence to quantify the savings in the number of generated condent rules compared to the brute-force method.
4. Identify top 5 association rules for each combination of support and confidence thresholds and discuss them.  
5. Instead of confidence, use lift as your measure of rule interestingness. Identify top 5 rules for each of the previous situations and discuss the relationship between confidence and lift.

Consider that the input to your program is a sparse matrix where the rows are transactions and columns are items. Each value in your matrix is a binary
variable from {0,1) that indicates presence of an item in the transaction.

Please read the report for details about implementation and its analysis.
