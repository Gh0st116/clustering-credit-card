# clustering-credit-card
Clustering credit card users behaviors based on their banking habits. Made with an Alura course.

This ML model was made to clusterize (separate customers based that share similar characteristics) bank customer data. We get all their information, clusterize and select the cluster centroids with the most variance that could be useful for us, such as balance or purchases.

<br>

At the end of the project, we could successfully separate customers into 5 clusters according to their behavior, them being:
- Cluster 1: Most purchases. Best payers.
- Cluster 2: Most cash advance and payments. Average payers.
- Cluster 3: Least cash advance. Biggest credit limit. Good payers. Biggest number of clients.
- Cluster 4: Least credit limit. Bad payers. Least clients.
- Cluster 5: Great balance. Least purchases. Worst payers. big number of clients.

<br>

## Dataset used
https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

<br>

## Technologies used
- Scikit-Learn
- MatPlotLib Pyplot
- Seaborn
- Pandas
