art-influence
=============

This maps how artists influence each other according to Wikipedia.

Nodes represent people. An edge from node A to node B indicates that person A was influenced by person B. The larger the node, the more people that person has influenced in the network. Created using Gephi and structured wikipedia data from dbpedia. 

The entire network
==================
![1 Untrimmed Network](https://github.com/coreylynch/art-influence/raw/master/full_graph.png)


Picasso's Neighborhood
======================
This is Picasso's ego network, i.e. the people he influenced, was influenced by, and the connections between them. Different colors correspond to different communities within his network.
![1 Picasso Black](https://github.com/coreylynch/art-influence/raw/master/picasso_black.png)

![1 Picasso White](https://github.com/coreylynch/art-influence/raw/master/picasso_white.png)

The Kurdish poet satellite
==========================
![1 Kurdish Poets](https://github.com/coreylynch/art-influence/raw/master/kurdish_poets.png)

Some big disclaimers:
* The influence relationship on dbpedia isn't weighted by how influential an artist was *relative to other influences*. Reality is probably much more complicated.
* Western bias. http://en.wikipedia.org/wiki/Wikipedia:BIAS

Thanks to http://architects.dzone.com/articles/how-use-gephi-visualize ! 