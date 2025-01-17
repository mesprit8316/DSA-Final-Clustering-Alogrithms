# DSA-Final-Clustering-Alogrithms
Final Project for group Hydra (Conor, Tucker, Kyle) for block 2 Data Structures and Algorithms


Goals:
Our goal for this project was to implement and test a variety of clustering algorithms. We wanted to observe how the runtime and clustering changed between algorithms depending on graph densities and shapes. We implemented 4 clustering algorithms: DBSCAN, K-Means, Hierarchichal Clustering, and Spectral Clustering. 


Methods:
- Dataset Methods: These methods (found in dataset_methods.py) are called with an argument for how many points should be made, and return a list of that many tuples arranged in a specific pattern depending on the data set.
- DBScan(graph, bag): The DBScan method (found in DBScan.py) takes arguments of a graph, and a bag data stucture. The return type is a dictionary which can be used to visualize clusters with nx.draw_networkx
- 



Experiment:
We tested each clustering algorithm on toy datasets of 5 different shapes. We wanted to see how each algorithm clustered the dataset (ie, could our implementations differentiate between different clusters the way we would cluster them) and how runtimes of each algorithm changed with varying point counts and densities. 



Results:
We found K-Means to be the fastest on all sets, regardless of density. We found our DBScan to be much slower than this, but with the advantage of more accurate clusters, and not having to specify the amount of clusters. Hierarchichal clustering was much slower than both, and took too long to realistically run on all five datasets of 1000 points. More information on our results can be found in (PLACEHOLDER FOR SLIDE DECK)
