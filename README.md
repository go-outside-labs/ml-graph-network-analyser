# NetAna - Complex Network Analysis Package

Extraction and analysis of several graph features from publicly available datasets using NetworkX. 

[Check out my paper with some interesting results](http://bt3gl.github.io/projects_page/html_files/mloutputs.html) and [check out my final report](final_report.pdf).


### Analyzed Features

* Assortativity
* Clique number
* Clustering
* Density
* Diameter
* Edge connectivity
* Node connectivity
* Number of cliques
* Number of edges
* Number of nodes
* Radius
* Clustering and Transitivity
* Betweenness centrality
* Closeness centrality
* Communicability centrality
* Coreness
* Degree centrality
* Eccentricity
* Number of triangles
* Pagerank
* Square clustering
* Transitivity

### Networks

* **Social networks**: online social networks, edges represent interactions between people
* **Ground truth**: ground-truth network communities in social and information networks
* **Communication**: email communication networks with edges representing communication
* **Citation**: nodes represent papers, edges represent citations
* **Collaboration**: nodes represent scientists, edges represent collaborations (co-authoring a paper)
* **Web graphs**: nodes represent webpages and edges are hyperlinks
* **Products**: nodes represent products and edges link commonly co-purchased products
* **p2p**: nodes represent computers and edges represent communication
* **Roads**: nodes represent intersections and edges roads connecting the intersections
* **Autonomous systems**: graphs of the Internet
* **Signed networks**: networks with positive and negative edges (friend/foe, trust/distrust)
* **Location-based networks**: Social networks with geographic check-ins
* **Wikipedia**: Talk, editing and voting data from Wikipedia
* **Bio Atlas**: Food-webs selected from Ecosystem Network Analysis site and from ATLSS.
* **Bio-Cellular**: Substrate in the cellular network of the corresponding organism.
* **Bio Metabolic**: Metabolic network of corresponding organism.
* **Bio Carbon**: Carbon exchanges in the cypress wetlands of South Florida during the wet and dry season.
* **Bio Yeast**: Protein-protein interaction network in budding yeast.



### Normalization and Graph Sampling

Performed using snowball sampling (choosing the sample order, i.e. number of nodes). Optimized for the number of edges and multiple samplings.


### Next Steps


* [Cleanse the data here.](https://github.com/bt3gl/NetClean-Complex-Networks-Data-Cleanser)

* [Classify the networks with lots of machine learning techniques here.](https://github.com/bt3gl/MLNet-Classifying-Complex-Networks)


----


## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). 
