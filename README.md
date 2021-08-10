# awesome-graph

A curated list of resources for graph databases and graph computing tools

## Graph databases

* [AgensGraph](https://bitnine.net/agensgraph-2/) - multi-model graph database with SQL and Cypher support
* [AnzoGraph](https://www.cambridgesemantics.com/anzograph/) - Massively parallel graph database with advanced analytics (SPARQL, Cypher, OWL/RDFS+, LPG) 
* [Atomic-Server](https://crates.io/crates/atomic-server/) - open-source type-safe graph database server with GUI, written in rust. Supports [Atomic Data](docs.atomicdata.dev/), JSON & RDF.
* [ArangoDB](https://www.arangodb.com/) - highly available Multi-Model NoSQL database
* [Blazegraph](https://github.com/blazegraph/database) - GPU accelerated graph database
* [Cayley](https://github.com/cayleygraph/cayley) - open source database written in Go
* [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction) - cloud-based multi-model database with support for TinkerPop3
* [Dgraph](https://dgraph.io) - Fast, Transactional, Distributed Graph Database (open source, written in Go)
* [DSE Graph](https://www.datastax.com/products/datastax-enterprise-graph) - Graph layer on top of DataStax Enterprise (Cassandra, SolR, Spark)
* [Grafito](https://github.com/arturo-lang/grafito) - Portable, Serverless & Lightweight SQLite-based Graph Database in Arturo
* [Grakn.AI](https://grakn.ai/) - a distributed hyper-relational database for knowledge-oriented systems, i.e. a distributed knowledge base
* [Graphd](https://github.com/google/graphd) - the Metaweb/Freebase Graph Repository
* [JanusGraph](http://janusgraph.org) - an open-source, distributed graph database with pluggable storage and indexing backends
* [Memgraph](https://memgraph.com/) - High Performance, In-Memory, Transactional Graph Database
* [Neo4j](http://tinkerpop.apache.org/docs/current/#neo4j-gremlin) - OLTP graph database
* [Nebula Graph](http://nebula-graph.io/) - A distributed, fast open-source graph database featuring horizontal scalability and high availability
* [RedisGraph](https://oss.redislabs.com/redisgraph/) - Property graph database, based on linear algebra constructs (GraphBLAS)
* [Sparksee](http://www.sparsity-technologies.com/#sparksee) - makes space and performance compatible with a small footprint and a fast analysis of large networks
* [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support
* [OrientDB](http://orientdb.com/orientdb/) - Distributed Multi-Model NoSQL Database with a Graph Database Engine
* [TerminusDB](https://github.com/terminusdb/terminusdb) is an open source graph database and document store. It is designed for collaboratively building data-intensive applications and knowledge graphs.
* [TigerGraph](https://www.tigergraph.com/) - The First Native Parallel Graph capable of real-time analytics on web-scale data
* [Weaviate](https://github.com/semi-technologies/weaviate) - Weaviate is a cloud-native, modular, real-time vector search engine with a graph data model (GraphQL interface) built to scale your machine learning models.

### Triple stores
* [Akutan](https://github.com/eBay/akutan) - Akutan is a distributed knowledge graph store, sometimes called an RDF store or a triple store
* [AllegroGraph](https://franz.com/agraph/allegrograph/) - high-performance, persistent graph database that scales to billions of quads
* [Apache Jena](https://jena.apache.org/) - open source Java framework for building Semantic Web and Linked Data applications
* [Dydra]( http://docs.dydra.com/dydra) - Dydra is a cloud-based graph database. Dydra stores data is natively stored as a property graph, directly representing the relationships in the underlying data.
* [Eclipse RDF4J](http://rdf4j.org/) - (formerly known as Sesame) is an open source Java framework for processing RDF data. This includes parsing, storing, inferencing and querying of/over such data. It offers an easy-to-use API that can be connected to all leading RDF storage solutions. It allows you to connect with SPARQL endpoints and create applications that leverage the power of linked data and Semantic Web.
* [GraphDB](http://graphdb.ontotext.com/graphdb/) - enterprise ready Semantic Graph Database, compliant with W3C Standards
* [Virtuoso](https://virtuoso.openlinksw.com/) - a "Data Junction Box" that drives enterprise and individual agility by deriving a Semantic Web of Linked Data from existing data silos
* [Hoply](https://github.com/amirouche/hoply/) - explore bigger than RAM relational data in the comfort of Python.

## Graph computing frameworks

* [Apache Giraph](https://giraph.apache.org/) - an iterative graph processing system built for high scalability
* [Apache TinkerPop](https://tinkerpop.apache.org/) - a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP)
* [Apache Spark - GraphX](https://spark.apache.org/graphx/) - Apache Spark's API for graphs and graph-parallel computation
* [GraphScope](https://github.com/alibaba/GraphScope) - A one-stop large-scale graph computing system from Alibaba

## Languages

* [Cypher](http://www.opencypher.org/)
* [Datalog](https://en.wikipedia.org/wiki/Datalog)
* [Gremlin](https://tinkerpop.apache.org/gremlin.html)
* [SPARQL](https://en.wikipedia.org/wiki/SPARQL)
* [GSQL](https://docs.tigergraph.com/)

## Managed hosting services

* [CosmosDB @ Microsoft](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction)
* [JanusGraph @ IBM Compose](https://www.compose.com/databases/janusgraph)
* [JanusGraph @ Google Cloud Platform](https://cloud.google.com/solutions/running-janusgraph-with-bigtable) - JanusGraph on Google Kubernetes Engine backed by Google Cloud Bigtable
* [JanusGraph @ Amazon Web Services Labs](https://github.com/awslabs/dynamodb-janusgraph-storage-backend)
* [Neo4j @ Graphene](https://www.graphenedb.com/)
* [Neptune @ Amazon Web Services](https://aws.amazon.com/neptune/) - a fast, reliable, fully-managed graph database service that makes it easy to build and run applications that work with highly connected datasets

## Learning materials

### Official documentations
* [Cypher](https://neo4j.com/developer/cypher-query-language/) - reference documentation
* [Gremlin](http://tinkerpop.apache.org/docs/current/reference/#traversal) - reference documentation

### Community effort
* [Graph Book](https://github.com/krlawrence/graph) - TinkerPop3 centric book written by [Kelvin R. Lawrence](https://twitter.com/gfxman)
* [SQL2Gremlin](http://sql2gremlin.com/) - transition from SQL to Gremlin by [Daniel Kuppitz](https://twitter.com/dkuppitz)
* [The Gremlin Compendium](http://www.doanduyhai.com/blog/?p=13460) - minimum survival kit for any Gremlin user, 10 blog post series by [Doan DuyHai](https://twitter.com/doanduyhai)

### Blogs
* [TigerGraph Blog](https://www.tigergraph.com/blog/)

## Conferences

* [Graph Connect](http://graphconnect.com/) - powered by Neo4j
* [Graph Day](http://graphday.com/) - an Independent Graph Conference from the Data Day folks

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jean-Baptiste Musso](https://github.com/jbmusso) has waived all copyright and related or neighboring rights to this work.
