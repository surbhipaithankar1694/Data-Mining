# Building a recommendation system

Data Source: http://grouplens.org/datasets/movielens/

##Basic Principle: 
For each user i and each movie j they did not see, and top k most similar users to i who have seen j
and then use them to infer the user i's rating on movie j.  
Handle all exceptions in a reasonable way e.g., if you cannot and k users for some movie j, then take all
users who have seen it.

Please read the report for details about implementation.
