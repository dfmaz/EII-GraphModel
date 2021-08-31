# EII-GraphModel

### Multi-Graph Model approach for analyzing the network of collaborating companies of the School of Industrial Engineering of the University of Extremadura.

A collaborated company is understood to be one that has an internship agreement with the school. The nodes of the network are formed by their own
companies and the connection criteria has been established as follows:
- Two companies will be connected to each other if they admit students of the same degree.
- In addition, a weight has been given to each node based on the number of students that each company has admitted to date.

In this way, you will be able to determine, on the one hand, which are the companies that have a more interdisciplinary, that is, those that welcome students of different degrees and, on the other hand, which are the companies that host a greater number of students.

[Networkx python package](https://networkx.org/) is the main library used in this notebook.
Finally, the nodes of the network have been placed in a geographical map using the [Basemap package](https://matplotlib.org/basemap/), generating the following figure:

![graph_map](/Img/graph_map.jpg)
