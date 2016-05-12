# Average Path Length in Small World Networks

We have written an implementation using *Dijkstra's Algorithm* to calculate the average shortest path length of nodes in a Small World Networks, which is generated using the *Watts and Strogatz model*, visualized with the vis.js API.
The code can be seen at *network.html* (preview at http://htmlpreview.github.io/?http://github.com/gmtuca/SmallWorldNetworks/blob/master/network.html).

The time taken to compute the algorithm and average path length are displayed under the browser's console (F12 on Google Chrome).

In order to start the demonstration simply **press SPACE**.

The following parameters can be passed to the webpage for customization:
- **N** (default 30) number of nodes in the network
- **K** (default 4) out/in degree of each node (must be even)
- **P** (default 0.15) probability of rewiring on Watts and Strogatz model
- **T** (default: 100) time (ms) delay between drawing of edges in the demo

Example: *network.html?N=30&K=4&P=0.2*

Keep in mind that the UI cannot handle a very large amount of nodes/edges.

Slides can be found at https://docs.google.com/presentation/d/1kMoNlmsFh90n-FqlgHeN6s3AhAFEkfkgBpZD0GG6orU

Performance benchmarks can be found at https://docs.google.com/spreadsheets/d/1ku8zYJJQfn9kzJI1QJ0nHbaMyWxg_tI5g2zf1iu4p_E