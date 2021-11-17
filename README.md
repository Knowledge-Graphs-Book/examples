# Knowledge Graphs book: examples

This repository contains examples in concrete syntaxes for the Knowledge Graphs book by Hogan et al, which is [freely available online](https://kgbook.org/), with copies and ebooks available for purchase from [Morgan & Claypool](http://www.morganclaypoolpublishers.com/catalog_Orig/product_info.php?products_id=1683).

## Overview

The book provides examples in an abstract graphical notation in order to be friendly to newcomers, and to avoid them getting "bogged down" in details relating to syntax.  Nevertheless, for newcomers that are interested to learn how these theoretical concepts are implemented in practice, in this repository we provide concrete implementations of the examples and figures of our paper in various languages and syntaxes.

The examples are divided into folders for each subsection according to [the book](https://kgbook.org/).
To find a particular example you can also search by the name of a particular figure in the repository (e.g., "figure_3_9_a", "table_4_1", etc.).
We may include multiple syntaxes/languages for some examples, indicated with different file extensions.

Since many different file formats and standards are used in this repository, we include pointing to the documentation of the respective standards, indicate where you can try out the examples online, or otherwise where you can find code relating to the example.

## Resources

The following is a list of resources tht the respective examples link to:

* [RDFShape](https://rdfshape.weso.es/) (RDF, RDFS, OWL, SHACL, ShEx)
* [RDF Playground](http://rdfplayground.dcc.uchile.cl/) (RDF, RDFS, OWL, SHACL, ShEx)
* [Neo4j Sandbox](https://sandbox.neo4j.com/) (Cypher/Property Graphs)
* [RDF* Implementations](https://github.com/w3c/rdf-star) (RDF*)
* [AnQL](https://github.com/nunolopes/anql) (Annotated RDF/AnQL)
* [RIF Implementations](https://www.w3.org/2005/rules/wiki/Implementations) (Rules)
* [Virtuoso's SPARQL-BI](https://medium.com/virtuoso-blog/graph-analytics-using-virtuosos-sparql-bi-extensions-to-sparql-5e75b4be32b3) (Graph analytics on RDF)
* PageRank in [Giraph](https://github.com/usi-systems/giraph-pagerank), [GraphX](https://spark.apache.org/docs/1.6.1/api/java/org/apache/spark/graphx/lib/PageRank.html), [Signal/Collect](https://uzh.github.io/signal-collect/)
* [TransE visualisations](http://www.ccri.com/2018/06/27/use-transe-effectively/)
* [OpenKE](https://github.com/thunlp/OpenKE) (Implementations of TransE, TransH, TransR, TransD, DistMult, RESCAL, HoIE, ComplEx, SimplE, etc.)
* [GNNs in Pytorch](https://towardsdatascience.com/hands-on-graph-neural-networks-with-pytorch-pytorch-geometric-359487e221a8) (GraphSAGE)
* [AMIE+](https://github.com/samehkamaleldin/amie_plus) (Rule Mining)
* [DL Learner](https://dl-learner.org/) (DL Axiom Mining)
* [DBpedia Spotlight](https://www.dbpedia-spotlight.org/demo/) (Entity Linking)
* [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/?) (Relation Extraction)
* [lod.live](http://en.lodlive.it/) (Linked Data Browser)
* [Q&D Browser](http://graphite.ecs.soton.ac.uk/browser/) (Linked Data Browser)

## Contributing

Please feel free to submit [bug reports](https://github.com/Knowledge-Graphs-Book/examples/issues) and [pull requests](https://github.com/knowledge-graphs-tutorial/examples/pulls)!

For example, if you are a lecturer and structure your slides after the paper, you might create additional examples or step-by-step calculations to explain the paper's concepts to your students.
Feel free to add those to this repository!

## License

![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)

To the extent possible under law, the contributors waive all copyright and related or neighboring rights to the contents of this repository.

## Source

If you wish to cite this source, you can use:

```bibtex
@book{kg-book,
  author = {Hogan, Aidan and Blomqvist, Eva and Cochez, Michael and
d'Amato, Claudia and de Melo, Gerard and Guti\'errez, Claudio and
Kirrane, Sabrina and Labra Gayo, Jos\'e Emilio and Navigli, Roberto and
Neumaier, Sebastian and Ngonga Ngomo, Axel-Cyrille and Polleres, Axel and
Rashid, Sabbir M. and Rula, Anisa and Schmelzeisen, Lukas and
Sequeda, Juan F. and Staab, Steffen and Zimmermann, Antoine},
  doi = {10.2200/S01125ED1V01Y202109DSK022},
  isbn = {9781636392363},
  language = {English},
  number = {22},
  numpages = {237},
  publisher = {Morgan \& Claypool},
  series = {Synthesis Lectures on Data, Semantics, and Knowledge},
  title = {{K}nowledge {G}raphs},
  url = {https://kgbook.org/},
  year = {2021}
}
```