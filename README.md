# Awesome Graph Universe 🌐

Welcome to **Awesome Graph Universe**, a curated list of resources, tools, libraries, and applications for working with graphs and networks. This repository covers everything from **Graph Databases** and **Knowledge Graphs** to **Graph Analytics**, **Graph Computing**, and beyond.

Graphs and networks are essential in fields like data science, knowledge representation, machine learning, and computational biology. Our goal is to provide a comprehensive resource that helps researchers, developers, and enthusiasts explore and utilize graph-based technologies.

Feel free to contribute by submitting pull requests! 🚀

## Table of Contents

<ul>
  <li><a href="#graph-databases">Graph Databases</a></li>
  <li><a href="#knowledge-graphs">Knowledge Graphs</a></li>
  <li><a href="#graph-data-science-and-analytics">Graph Data Science and Analytics</a></li>
  <li><a href="#graph-computing">Graph Computing</a></li>
  <li><a href="#graph-engines">Graph Engines</a></li>
</ul>

---

## Graph Databases

Graph databases are designed to store, manage, and query graph-structured data. They come in two main categories: **Property Graphs** and **Triple Stores**. Below are some key tools and their respective languages.

### Property Graph Databases

Property graphs allow nodes and edges to have associated properties, making them useful for more detailed graph representations.

- [Amazon Neptune](https://aws.amazon.com/neptune/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A managed graph database service that supports both RDF graphs (Triple Store) and property graphs.
- [ArangoDB](https://www.arangodb.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Multi-model database supporting graphs, documents, and key-value pairs.
- [JanusGraph](https://janusgraph.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - A scalable, distributed property graph database optimized for querying massive graphs.
- [KuzuDB](https://kuzudb.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - A highly scalable, extremely fast, easy-to-use embeddedable graph database.
- [Neo4j](https://neo4j.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - A leading native graph database with high-performance queries for large datasets.
- [OrientDB](https://orientdb.com/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A multi-model database supporting graphs and documents.
- [TigerGraph](https://www.tigergraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A fast, scalable graph database for enterprise applications and analytics.

### Triple Stores (RDF Databases)

Triple stores are designed to store and query RDF (Resource Description Framework) data, which represents information in triples: subject-predicate-object.

- [Amazon Neptune](https://aws.amazon.com/neptune/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A managed graph database service that supports both RDF graphs (Triple Store) and property graphs.
- [Blazegraph](https://blazegraph.com/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A high-performance triple store used for RDF data.
- [GraphDB](https://www.ontotext.com/products/graphdb/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - An RDF database that helps create and query linked data.
- [Stardog](https://www.stardog.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - An enterprise knowledge graph platform, fully compliant with RDF and SPARQL.

---

## Knowledge Graphs

Knowledge graphs connect data points into a rich semantic web of entities and relationships. They are often used in AI applications, search engines, and data integration platforms.

- [DBpedia](https://wiki.dbpedia.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-PHP-blueviolet) - A project aimed at extracting structured content from Wikipedia.
- [Google Knowledge Graph](https://developers.google.com/knowledge-graph) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Powering Google's search engine with structured knowledge representation.
- [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-JavaScript-yellow) - A free and open knowledge graph that can be queried and used in various applications.
- [YAGO](https://yago-knowledge.org/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A huge semantic knowledge base derived from Wikipedia, WordNet, and GeoNames.

---

## Graph Data Science and Analytics

Graph data science focuses on analyzing the structure and patterns in graphs to solve complex problems in domains like recommendation systems, fraud detection, and social network analysis.

- [GraphTool](https://graph-tool.skewed.de/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - An efficient Python module for manipulation and statistical analysis of graphs.
- [GraphX (Apache Spark)](https://spark.apache.org/graphx/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Scala-blue) - A component of Apache Spark for graph-parallel computation.
- [Neo4j Graph Data Science](https://neo4j.com/product/graph-data-science/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - A comprehensive library for graph algorithms and machine learning models.
- [NetworkX](https://networkx.github.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - A Python library for creating, manipulating, and studying complex networks.
- [TigerGraph Graph Studio](https://www.tigergraph.com/products/graph-analytics/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Powerful tools for exploring and analyzing graph data.

---

## Graph Engines

Graph engines are optimized systems for performing queries, computations, and analytics on large graph datasets, leveraging both hardware and software efficiencies.

- [AnzoGraph](https://www.cambridgesemantics.com/product/anzograph) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A massively parallel, in-memory graph database engine for advanced analytics.
- [Dgraph](https://dgraph.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Go-blue) - A fast, distributed graph database system designed for real-time query execution.
- [GunDB](https://gun.eco/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-JavaScript-yellow) - A decentralized graph database engine designed for distributed systems.
- [KuzuDB](https://kuzudb.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - A highly scalable, extremely fast, easy-to-use embeddedable graph database.
- [Memgraph](https://memgraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen)
- [PuppyGraph](https://www.puppygraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Seamlessly query one or multiple data stores as a unified graph model.
- [TigerGraph](https://www.tigergraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A real-time graph analytics platform that supports massive datasets and deep link analytics.

---

## Graph Computing

Graph computing refers to the infrastructure and platforms that handle large-scale graph processing, often distributed across multiple machines for speed and scalability.

- [Apache Giraph](http://giraph.apache.org/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A scalable graph processing system used by Facebook for social graph analysis.
- [GraphFrames (Apache Spark)](https://graphframes.github.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Scala-blue) - Combines the benefits of GraphX and DataFrames for scalable graph processing.
- [GraphLab](https://turi.com/products/create/docs/graphlab.html) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A high-performance, graph-based computation engine for machine learning applications.
- [Pregel](https://research.google/pubs/pub36726/) ![Status](https://img.shields.io/badge/status-na-lightgrey) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Google's graph processing model, inspired by Bulk Synchronous Parallel (BSP) systems.

---

## Contributing

Contributions are welcome! If you know of any valuable graph-related resources, tools, or libraries that should be included, feel free to submit a pull request or open an issue.

Please follow the [contribution guidelines](CONTRIBUTING.md) to maintain the quality and consistency of Awesome Graph Universe.

---

## License

[![CC0](https://img.shields.io/badge/license-CC0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This repository is licensed under CC0 1.0 Universal, which means you can freely use and contribute to this project.

---

Happy Graphing! 😊

---