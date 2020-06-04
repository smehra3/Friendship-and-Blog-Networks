# Measures-of-Centrality-on-Friendship-and-Blog-Networks

**Part 1 - A network of friendships at a university department, `G1`,. Each node corresponds to a person, and an edge indicates friendship. **

* Found degree centrality, closeness centrality, and normalized betweeness centrality (excluding endpoints) of a certain node
* If a user from this network were to be given an online shopping voucher that they would send to their friends, found who will be the best candidate for this vocher. 
Assumptions:
  * The voucher can be forwarded to multiple users at the same time, but the travel distance of the voucher is limited to one step, which means if the voucher travels more than one step in this network, it is no longer valid.
* If a user from this network were to be given an online shopping voucher that they would send to their friends, found who will be the best candidate for this vocher. 
Assumptions:
  * No limit on the voucher’s travel distance. Because the network is connected, regardless of who is picked, every node in the network will eventually receive the voucher. However, we now want to ensure that the voucher reaches the nodes in the lowest average number of hops.
* If the restriction on the voucher’s travel distance is still removed, but now a competitor has developed a strategy to remove a person from the network in order to disrupt the distribution of previous company’s voucher. The competitor is specifically targeting people who are often bridges of information flow between other pairs of people. Identified the single riskiest person to be removed under competitor’s strategy.

**Part 2 - `G2` is a directed network of political blogs, where nodes correspond to a blog and edges correspond to links between blogs**

* Applied Scaled Page Rank Algorithm to this network. Found the Page Rank of node 'realclearpolitics.com' with damping value 0.85.
* Found the 5 nodes with highest Page Rank.
* Used HITS Algorithm to find the hub and authority scores of node 'realclearpolitics.com'.
* Used HITS Algorithm to find the 5 nodes with highest hub scores and 5 nodes with highest authority scores.
