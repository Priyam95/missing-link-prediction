# Predicting Missing Links in an Actor Co-occurrence Network

An actor network consists of nodes which represent actors and the edges between two nodes stand for co-occurrence on the same Wikipedia page. This is a proxy for their joint participation in the same movie, for their personal relation, for their level of fame, etc.
In addition to the graph structure, each node (i.e., actor) is also associated with textual information processed from its Wikipedia page, from which some keywords were extracted. The edges were deleted at random from a graph.
Utilizing the information from both the underlying actor network and the processed Wikipedia description, the task was to accurately reconstruct the initial network using both graph-theoretical and node feature information. 
