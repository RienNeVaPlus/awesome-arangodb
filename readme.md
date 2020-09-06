# Awesome ArangoDB 🥑 [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
> Carefully curated list of awesome ArangoDB resources.

[Contributions](./contributing.md) welcome. Add links through [pull requests](https://github.com/RienNeVaPlus/awesome-arangodb/pulls) or create an [issue](https://github.com/RienNeVaPlus/awesome-arangodb/issues) to start a discussion.
 
<sup>*Note: <code>\*</code> indicates an official ArangoDB resource.*</sup>

![divider](divider.small.png)
### Contents

1. [What is ArangoDB](#what-is-arangodb)
2. [What are Foxx Microservices](#what-are-foxx-microservices)
3. [Tutorials](#-tutorials)
4. [Links](#-links)
5. [Documentation](#-documentation)
6. [Tools](#-tools)
7. [Drivers](#-drivers)
8. [Awesome Repositories](#-awesome-repositories)
9. [Awesome Articles](#-awesome-articles)
10. [Awesome Videos](#-awesome-videos)

![divider](divider.png)

### What is ArangoDB

ArangoDB is a native [multi-model database](https://en.wikipedia.org/wiki/Multi-model_database) system developed by [ArangoDB GmbH](https://www.arangodb.com). The database system supports three data models (key/value, documents, graphs) with one database core and a unified query language AQL (ArangoDB Query Language). The query language is declarative and allows the combination of different data access patterns in a single query. ArangoDB is a NoSQL database system but AQL is similar in many ways to SQL. 

- Watch the official introduction: 🎞️ [Modern data modeling: Multi-Model approach using ArangoDB](https://www.youtube.com/watch?v=on1l2pEEWnw)*
- Or start with a real-world example: 🎞️ [An e-commerce app in action built on top of a multi-model database](https://youtu.be/lF1Bd-NYmAk?t=55)*
- Or scroll some text: 📰 [ArangoDB in 10 Minutes: CRUD](https://www.arangodb.com/tutorials/arangodb-crud/)*

![divider](divider.small.png)

### What are Foxx Microservices

ArangoDB allows application developers to write their data access and domain logic as microservices running directly within the database with native access to in-memory data. The Foxx microservice framework makes it easy to extend ArangoDB’s own REST API with custom HTTP endpoints using modern JavaScript running on the same V8 engine you know from Node.js and the Google Chrome web browser.

- 📰 Read more on [Foxx Microservices](https://www.arangodb.com/docs/stable/foxx.html)*

![divider](divider.png)

### 🔗 Links
- [ArangoDB.com](http://www.arangodb.com)*
- [Download ArangoDB](https://www.arangodb.com/download-major/)*
- [GitHub](https://github.com/arangodb/arangodb)*
- [Slack](https://slack.arangodb.com/)*
- [Twitter](https://twitter.com/arangodb)*
- [YouTube](https://www.youtube.com/user/ArangoDB)*
- [Google Groups](https://groups.google.com/forum/#!forum/arangodb)*
- [Stack Overflow](https://stackoverflow.com/questions/tagged/arangodb)

![divider](divider.small.png)

### 📗 Tutorials
- [Getting Started](https://www.arangodb.com/docs/stable/getting-started.html)*
- [Tutorial Overview](https://www.arangodb.com/docs/stable/tutorials.html)*
- [Training Center](https://www.arangodb.com/arangodb-training-center/)*
- [Cookbook](https://www.arangodb.com/docs/stable/cookbook/index.html)*
- [Udemy Video Course](https://www.udemy.com/getting-started-with-arangodb/)* - Getting started with ArangoDB

![divider](divider.small.png)

### 📚 Documentation
- [Manual](https://www.arangodb.com/docs/stable/)* - Handbook
- [AQL](https://www.arangodb.com/docs/stable/aql/)* - ArangoDB Query Language
- [HTTP](https://www.arangodb.com/docs/stable/http/)* - HTTP API
- [Drivers](https://www.arangodb.com/docs/stable/drivers/)*

![divider](divider.small.png)

### 🛠️ Tools
- [ArangoDB Server](https://www.arangodb.com/docs/stable/programs-arangod.html)* - The ArangoDB daemon (`arangod`) is the central server binary, which can run in different modes for a variety of setups like single server and clusters.
- [Web Interface](https://www.arangodb.com/docs/stable/programs-web-interface.html)* - The Web Interface (also `Aardvark`, `frontend` or `Web UI`) can be accessed with a browser under the URL `http://localhost:8529` with default server settings.
- [ArangoDB Shell](https://www.arangodb.com/docs/stable/programs-arangosh.html)* - The ArangoDB shell (`arangosh`) is a command-line client tool that can be used for administration of ArangoDB servers.
- [ArangoDB Starter](https://www.arangodb.com/docs/stable/programs-starter.html)* - The ArangoDB Starter is a tool that can help you deploy ArangoDB in an easy way (either in single-instance, active/passive or Cluster mode).
- [Arangodump](https://www.arangodb.com/docs/stable/programs-arangodump.html)* - Arangodump is a command-line client tool to create backups of the data and structures stored in ArangoDB.
- [Arangorestore](https://www.arangodb.com/docs/stable/programs-arangorestore.html)* -Arangorestore is a command-line client tool to restore backups created by Arangodump to ArangoDB servers.
- [Arangoimport](https://www.arangodb.com/docs/stable/programs-arangoimport.html)* - Arangoimport is a command-line client tool to import data in JSON, CSV and TSV format to ArangoDB servers.
- [Arangoexport](https://www.arangodb.com/docs/stable/programs-arangoexport.html)* - Arangoexport is a command-line client tool to export data from ArangoDB servers to formats like JSON, CSV or XML for consumption by third-party tools.
- [Arangobench](https://www.arangodb.com/docs/stable/programs-arangobench.html)* - Arangobench is ArangoDB’s benchmark and test tool. It can be used to issue test requests to the database for performance and server function testing. It supports parallel querying and batch requests.
- [Arangoinspect](https://www.arangodb.com/docs/stable/programs-arangoinspect.html)* - Arangoinspect is a command-line client tool that collects information of any ArangoDB server setup to facilitate troubleshooting for the ArangoDB support.
- [Arango-dfdb](https://www.arangodb.com/docs/stable/programs-arango-dfdb.html)* - The ArangoDB Datafile Debugger can check datafiles for corruptions and remove invalid entries to repair them. Such corruptions should not occur unless there was a hardware failure.
- [Foxx CLI](https://www.arangodb.com/docs/stable/programs-foxx-cli.html)* - Foxx CLI is command line tool for managing and developing ArangoDB Foxx services. It is an optional tool which requires Node.js and can be installed via the package managers NPM and Yarn.

![divider](divider.small.png)

### ⚙️ Drivers
- **Clojure**
  - [clarango](https://github.com/Lepetere/clarango)
- **Go**
  - [ArangoDB Go Driver](https://godoc.org/github.com/arangodb/go-driver)*
  - [aranGO](https://github.com/diegogub/aranGO)
  - [arangolite](https://www.arangodb.com/docs/stable/drivers/)
  - [aranGoDriver](https://github.com/TobiEiss/aranGoDriver)
- **Java**
  - [ArangoDB Java Driver](https://github.com/arangodb/arangodb-java-driver)*
- **JavaScript**
  - [ArangoJS](https://github.com/arangodb/arangojs)*
  - [arangojs-extended](https://github.com/sogko/arangojs-extended)
- **.NET**
  - [ArangoDB-NET](https://www.arangodb.com/docs/stable/drivers/)
- **PHP**
  - [ArangoDB-PHP](https://github.com/arangodb/arangodb-php)*
  - [ArangoDB-PHP-Core](https://github.com/frankmayer/ArangoDB-PHP-Core)
- **Python**
  - [pyArango](http://www.github.com/tariqdaouda/pyArango)
  - [python-arango](https://github.com/Joowani/python-arango)
- **Scala**
  - [Scarango](https://github.com/outr/scarango)
- **Ruby**
  - [ArangoRB](https://github.com/StefanoMartin/ArangoRB)

![divider](divider.png)

### 🌵 Awesome Repositories

3rd party tools and extensions to use with ArangoDB. 

> 🔥 The list is maintained by [you](./contributing.md).

![divider](divider.small.png)
#### Adapters & connectors
- Sails.js: [sails-arangodb](https://github.com/gabriel-letarte/sails-arangodb)
- jugglingdb: [jugglingdb-arango](https://github.com/m0ppers/jugglingdb-arango)
- Loopback: [loopback-connector-arangodb](https://github.com/mrbatista/loopback-connector-arangodb)
- FeathersJS: [feathers-arangodb](https://github.com/AnatidaeProject/feathers-arangodb)
- Hemera: [hemera-arango-store](https://github.com/hemerajs/hemera-arango-store)
- nomatic-data: [nomatic-arangodb-adapter](https://github.com/bdfoster/nomatic-arangodb-adapter)
- JollofJS: [jollof-data-arangodb](https://github.com/iyobo/jollofjs/tree/master/packages/jollof-data-arangodb)
- deepstream: [deepstream.io-storage-arangodb](https://github.com/Brian-McBride/deepstream.io-storage-arangodb)

![divider](divider.small.png)
#### Boilerplates / Starter
- TypeScript: [arangodb-typescript-setup](https://github.com/RienNeVaPlus/arangodb-typescript-setup)

![divider](divider.small.png)
#### Command line interfaces
- [foxx-cli](https://github.com/arangodb/foxx-cli)* - CLI for managing and developing ArangoDB Foxx services.
- [Arangler](https://github.com/internalfx/arangler) - A command line tool to ease development and administration.

![divider](divider.small.png)
#### ORMs, ODMs and similar
- [type-arango](https://github.com/RienNeVaPlus/type-arango) - Powerful decorators for ArangoDB Foxx Apps when working with TypeScript.
- [orongo](https://github.com/roboncode/orango) - ArangoDB Object Modeling for Node.js, Foxx and Modern Web Browsers.
- [pims](https://github.com/UnwrittenFun/pims) - An ORM for document-oriented database systems, written in and for TypeScript.
- [ignitor](https://github.com/TylerGarlick/ignitor.js) - Ignitor is a ArangoDB Object Data Modeling (ODM) framework similar to mongoose.
- [caminte](https://github.com/biggora/caminte) - CaminteJS is cross-db ORM for Node.js, providing common interface to access most popular database formats.
- [arangetrum](https://github.com/mustertech/arangetrum) - 
Simple library to create and use models for ArangoDB.

![divider](divider.small.png)
#### AQL
- [ArangoDB Query Builder](https://github.com/arangodb/aqbjs)* (deprecated) - The query builder allows constructing complex AQL queries with a pure JavaScript fluid API.
- [mongo-aql](https://github.com/k-components/mongo-aql) - A mongo-like interface for aql generation.
- [Arangolize](https://github.com/OKNoah/final/tree/master/packages/arangolize) - Build find queries in a Sequelize-like way.

![divider](divider.small.png)
#### Miscellaneous
- [arangodb-error-codes](https://github.com/oprogramador/arangodb-error-codes) - ArangoDB 3 error codes according to the official documentation.
- [arangochair](https://github.com/baslr/arangochair) - Pushes ArangoDB changes in realtime to the client.
- [arangodep](https://github.com/kaerus/arangodep) - Arango deployment tools.
- [ArangoDB Timetravel:](https://developers.bonsaya.com/) - ArangoDB Timetravel is a time-sliced wrapper over the existing ArangoDB Foxx functionality that allows the traversal of your data in time.
- [RecallGraph](https://github.com/RecallGraph/RecallGraph) - A versioning data store for time-variant graph data.
RecallGraph is a versioned-graph data store - it retains all changes that its data (vertices and edges) have gone through to reach their current state. It supports point-in-time graph traversals, letting the user query any past state of the graph just as easily as the present.

![divider](divider.png)

### 📰 Awesome Articles
- ArangoDB database setup for a beginner [medium.com@mrinalbarua](https://medium.com/@mrinalbarua/arangodb-database-setup-for-a-beginner-bbad6bda16e6) - *2019-02-5*
- Graphical Interpretation of data using ArangoDB - [medium.com@pranshumalviya](https://medium.com/@pranshumalviya/graphical-interpretation-of-data-using-arangodb-8d8e5ef7c622) - *2017-12-28*
- ArangoDB: The new Graal? - [dev.to@solisoft](https://dev.to/solisoft/arangodb--the-new-graal--part-1-6g8) - *2017-11-16*
- Using Webpack with ArangoDB and Foxx - [hackernoon.com](https://hackernoon.com/using-webpack-with-arangodb-and-foxx-720d411ff2fe) - *2017-04-11*
- ArangoDB and GraphQL - [mikewilliamson.wordpress.com](https://mikewilliamson.wordpress.com/2017/03/24/arangodb-and-graphql/) - *2017-03-24*
- Using Typescript for programming ArangoDB FOXX services - [devblog.ztp.pt](http://devblog.ztp.pt/using-typescript-for-programming-arangodb-foxx-services/) - *2016-10-23*
- Using GraphQL with NoSQL database ArangoDB - [arangodb.com](https://www.arangodb.com/2016/02/using-graphql-nosql-database-arangodb/) - *2016-02-17*
- Data modeling with multi-model databases - [oreilly.com](https://www.oreilly.com/ideas/data-modeling-with-multi-model-databases) - *2015-07-07*

![divider](divider.png)

### 🎞️ Awesome Videos
- ArangoDB Graph Database Syntax - [YouTube@ArangoDB](https://youtu.be/0U8TfLOp184) - *2019-04-18*
- GraphQL and ArangoDB - [YouTube@ArangoDB](https://youtu.be/vaUdiWU-src) - *2017-04-27*
- Andreas Jung – The hunt for the right NoSQL database. Why we love ArangoDB - [YouTube@PyMunich](https://youtu.be/Fi8oO_MkkWo) - *2016-11-18*

![divider](divider.png)

### 🧾 License
[MIT](LICENSE)

![divider](divider.png)

### 🐱‍👤 Contributors
- [RienNeVaPlus](https://github.com/RienNeVaPlus)
