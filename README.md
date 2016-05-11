# Average Path Length in Small World Networks

We have written an implementation to calculate the average shortest path length of Small World Networks, as seen in *network.html* (preview at http://htmlpreview.github.io/?http://github.com/gmtuca/SmallWorldNetworks/blob/master/network.html).

The graph is generated using the *Watts and Strogatz model* visualized with the vis.js API, followed by calculation of the path lengths with our implementation of *Dijkstra's Algorithm*.

The following parameters can be passed to the webpage for customization:
- **N** number of nodes in the network
- **K**   out/in degree of each node (must be even)
- **P**   probability of rewiring on Watts and Strogatz model

Example: *network.html?N=20&K=6&P=0.2*

Slides can be found at https://docs.google.com/presentation/d/1kMoNlmsFh90n-FqlgHeN6s3AhAFEkfkgBpZD0GG6orU
