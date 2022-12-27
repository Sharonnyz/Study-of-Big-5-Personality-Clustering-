# Study of Big 5 Personality

This work is to use the Facebook statuses and network features to cluster the 250 users and explore the relationship between Big 5 personality and each cluster, i.e., match cluster results with the Big 5 personality traits. 

## Dataset
Mypersonality.csv

The dataset contains information about 250 Facebook users, 15 variables, 9917 records including Facebook statuses in raw texts and network features (network size, betweenness centrality, density, brokerage and transitivity) as independent variables. These 250 users were made to answer 100 item long version of IPIP questioners, this yielded big5 personality values and categories (y/n) as the personality class (gold standard). In the dataset, only the final categorial variables in Big5 personality dimensions are included.

Personality of an individual is categorized into Big5 personality traits, which includes:
- Extraversion(x) (sociable vs shy: y/n of cEXT)
- Neuroticism(n) (neurotic vs calm: y/n of cNEU)
- Agreeableness(a) (friendly vs uncooperative: y/n of cAGR)
- Conscientiousness(c) (organized vs careless: y/n of cCON) 
- Openness(o) (insightful vs unimaginative: y/n of cOPN).

## Natural Language Process

The final samples for clustering had 250 observations and 147 features.


## Clustering
This work uses two methods to determine the optimal number of clusters for the data set, the elbow method and the average silhouette method.

Utilizes two clustering method:
- K-Means Clustering
- Hierarchical Clustering

## Cluster Membership with Big 5 Personality Traits
To explore whether significant differences existed among the clusters regarding personality class, this work conducts one-way analysis of variance (ANOVA). 

The study demonstrates the distribution in all clusters for specific personality class by bar charts.

From another dimension， this work depicts the distribution for Big5 personality traits in each cluster by bar charts.
