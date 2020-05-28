# Instacart Market Basket Analysis

This Jupyter notebook is based on the [Kaggle competition with the same name](https://www.kaggle.com/c/instacart-market-basket-analysis).

The dataset contains around 3 million orders of a grocery store, separated in 5 dataframes. Users are identified by their IDs, and it is possible to track their purchase history. All products are also identified by their IDs and can be tracked to aisles and departments. Purchases are timestamped.

I do not deal with the competition challenge. Instead, I take advantage of this extensive dataset for data exploration and the creation of association rules. For this second part, the package usually suggested for association rules is not suited due to memory constraints, therefore I had to develop my own implementation of the apriori algorithm, relying on generators to limit memory consumption.
