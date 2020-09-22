### Github Collaborator Recommendation
> Goal:
>+ Given a directed social graph, predict missing links to recommend users

> Data Description:
>+ Source: http://snap.stanford.edu/data/github-social.html
>+ A large social network of GitHub developers which was collected from the public API in June 2019. Nodes are developers who have starred at least 10 repositories and edges are mutual follower relationships between them. The vertex features are extracted based on the location, repositories starred, employer and e-mail address. The task related to the graph is binary node classification - one has to predict whether the GitHub user is a web or a machine learning developer. This target feature was derived from the job title of each user.

> Metrics: 
>+ Similarity measures (Jaccard & Cosine)
>+ Ranking measures
>+ Common neighbors
>+ Resouce allocation index
>+ preferential attachment

> Classification Methods:
>+ Logistic Regression
>+ Support Vector Mechine

> Reference:
>+ http://be.amazd.com/link-prediction/
