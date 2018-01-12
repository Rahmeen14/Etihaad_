We are going to address the issue of safety in our project named 
                                  ‘Etihaad’ i.e. Being precocious.
Delhi accounts for the maximum number of rape cases among 19 major cities at 40%, besides the highest crime rate in 2017, according to the data released by National Crime Records Bureau (NCRB) .
The national capital has got the dubious distinction of topping the list in cases of murder, kidnapping and abduction, juveniles in conflict and economic offences. Delhi reported 33% (13,803 cases out of total 41,761 cases in 19 cities) of total crimes against women, followed by Mumbai at 12.3% (5,128 cases) last year among the 19 cities with population above two million.


How we try to solve the problem?
Google map tries to find the fastest route between two paths even if it may mean compromising on security.
Our app aims at detecting the safest route by finding danger index of all possible paths between two places which is a weighted sum of numeric values our unsupervised machine learning algorithm devised and assigned to 166 places in Delhi .
We hope to extend that by including more detailed and transparent data which is not currently available.



Our Technical Complexity

We have applied Unsupervised Machine Learning Algorithm to find danger index of multiple routes between two places.

We have used a Classification algorithm : K-Means , to rate criminal activities of 166 places on the map of Delhi in range of 0 to 4.
K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity. The results of the K-means clustering algorithm are:
The centroids of the K clusters, which can be used to label new data
Labels for the training data (each data point is assigned to a single cluster)


