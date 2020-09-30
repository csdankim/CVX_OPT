# Large Scare Convex/Non-convex Optimization
## Topic Modeling by Solving Non-Convex Problem
&nbsp;

### Abstract

In this term's final project, I implemented and tested the Anchor-Free algorithm and compare its performance with two traditional topic modeling algorithms, LDA and NMF, and one unsupervised learning method, Kmeans Clustering. Anchor-word topic modeling has serious scalability and identification issues. To solve this problem, Separability / Anchor-Word assumption and Suciently Scattered assumption were studied as explained in [1]. The problem formulation for the algorithm found that it is a non-convex problem which cannot achieve the optimal solution directly. The feasible way to solve the non-convex problem is finding an approximate solution through iteration. Based on these ideas, the Anchor-Free algorithm for topic modeling is established. For the performance test, 6090 tweets regarding the climate-change were used, and the simulation results are provided.

&nbsp;
### The Experiment Results & Discussion
Please see the [report]().

&nbsp;

[1] [Kejun Huang, Xiao Fu, and Nicholas D. Sidiropoulos. Anchor-Free Correlated Topic Modeling: Identifiability and Algorithm. Advances in Neural Information Processing Systems (NIPS 2016), Dec. 2016, Barcelona, Spain]().