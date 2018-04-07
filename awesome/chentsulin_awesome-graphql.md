# Information comes from [chentsulin/awesome-graphql](https://github.com/chentsulin/awesome-graphql)
# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL & Relay

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [Specification](#spec)
- [Community](#community)
- [GraphQL Meetups](#meetups)
- [Libraries](#lib)
	- [Javascript](#lib-js)
	- [Typescript](#lib-ts)
	- [Ruby](#lib-rb)
	- [PHP](#lib-php)
	- [Python](#lib-py)
	- [Java](#lib-java)
	- [C/C++](#lib-c)
	- [Go](#lib-go)
	- [Scala](#lib-scala)
	- [Perl](#lib-perl)	
	- [.NET](#lib-dotnet)
	- [Erlang](#lib-erlang)
	- [Elixir](#lib-elixir)
	- [Haskell](#lib-haskell)
	- [SQL](#lib-sql)
	- [Lua](#lib-lua)
	- [Elm](#lib-elm)
	- [Clojure](#lib-clojure)
	- [ClojureScript](#lib-clojurescript)
	- [Swift](#lib-swift)
	- [OCaml](#lib-ocaml)
	- [Rust](#lib-rust)
	- [R](#lib-r)
	- [Julia](#lib-julia)
	- [Kotlin](#lib-kotlin)
	- [Unity](#lib-unity)
- [Tools](#tools)
- [Services](#services)
- [Databases](#databases)
- [Examples](#example)
	- [Javascript](#example-js)
	- [Typescript](#example-ts)
	- [Ruby](#example-rb)
	- [Go](#example-go)
	- [Scala](#example-scala)
	- [Python](#example-python)
	- [Elixir](#example-elixir)
	- [PHP](#example-php)
	- [ReasonML](#example-reasonml)
- [Videos](#video)
- [Blogs](#blogs)
- [Posts](#post)
- [Workshoppers](#workshopper)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specification

* [facebook/graphql](http://facebook.github.io/graphql/) - Working Draft of the Specification for GraphQL created by Facebook.

<a name="community" />

## Community

* [Slack](https://graphql.slack.com/messages/general) - Share and help people on the chat. Get your invite [here](https://graphql-slack.herokuapp.com/)
* [`#graphql` on Freenode](https://webchat.freenode.net/?channels=#graphql) - The official IRC channel for GraphQL
* [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing
* [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag [#graphql](https://twitter.com/search?q=%23GraphQL)
* [StackOverflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag [graphql](http://stackoverflow.com/questions/tagged/graphql)
* [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs :star:541
* [GraphQL World](https://graphql-world.com) - The fastest growing community of GraphQL developers

<a name="meetups" />

## GraphQL Meetups

* [Berlin](https://www.meetup.com/graphql-berlin/)
* [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
* [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
* [Istanbul](https://www.meetup.com/GraphQL-Istanbul/)
* [London](https://www.meetup.com/GraphQL-London/)
* [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
* [Munich](https://www.meetup.com/GraphQL-Munich/)
* [New York City](https://www.meetup.com/GraphQL-NYC/)
* [San Francisco](https://www.meetup.com/GraphQL-SF/)
* [Sydney](https://www.meetup.com/GraphQL-Sydney/)
* [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
* [Toronto](https://www.meetup.com/GraphQL-Toronto/)

<a name="lib" />

## Libraries

<a name="lib-js" />

### JavaScript Libraries

* [GraphQL.js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript. :star:10028
* [express-graphql](https://github.com/graphql/express-graphql) - GraphQL Express Middleware. :star:3214
* [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware. :star:523
* [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi. :star:109
* [codemirror-graphql](https://github.com/graphql/codemirror-graphql) - GraphQL mode and helpers for CodeMirror. :star:109
* [graphql-schema](https://github.com/devknoll/graphql-schema) - Create GraphQL schemas with a fluent/chainable interface. :star:128
* [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL. :star:1070
* [graphql-sequelize-crud](https://github.com/Glavin001/graphql-sequelize-crud) - Automatically generate queries and mutations from Sequelize models. :star:96
* [graffiti](https://github.com/RisingStack/graffiti) - Node.js GraphQL ORM. :star:1040
* [graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) - Mongoose (MongoDB) adapter for graffiti (Node.js GraphQL ORM). :star:393
* [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings. :star:66
* [adrenaline](https://github.com/gyzerok/adrenaline) - React bindings for Redux with Relay in mind. :star:727
* [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models. :star:159
* [graphql-bookshelfjs](https://github.com/weyoss/graphql-bookshelfjs) - A simple bridge between your graphql queries and your bookshelf models, perform batched and optimised queries. :star:15
* [graph.ql](https://github.com/matthewmueller/graph.ql) - Faster and simpler technique for creating and querying GraphQL schemas. :star:583
* [react-reach](https://github.com/kennetpostigo/react-reach) - A library to communicate with Graphql through Redux :star:123
* [Lokka](https://github.com/kadirahq/lokka) - Simple JavaScript client for GraphQL, which you can use anywhere. :star:1278
* [Strapi](http://strapi.io/documentation/graphql) - Open-source Node.js framework that supports "GraphQL" out of the box.
* [GraysQL](https://github.com/larsbs/graysql) - A GraphQL manager and loader. :star:25
* [graysql-orm-loader](https://github.com/larsbs/graysql-orm-loader) - A GraysQL extension to load a GraphQL schema from an ORM. :star:6
* [Annotated GraphQL](https://github.com/almilo/annotated-graphql) - Proof of Concept for annotations in GraphQL (i.e.: transform an existing REST api into a GraphQL endpoint). :star:1
* [Apollo Client](https://github.com/apollographql/apollo-client) - A well-documented GraphQL client. Has React and Angular bindings. :star:6705
* [graphql-tools](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers. :star:1740
* [graphql-anywhere](https://github.com/apollographql/graphql-anywhere) - Run a GraphQL query anywhere, against any data, with no schema. :star:568
* [graphql-tag](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries. :star:604
* [modelizr](https://github.com/julienvincent/modelizr) - A library for simplifying the process of writing GraphQL queries, mocking them and normalizing their responses. :star:155
* [vue-apollo](https://github.com/Akryum/vue-apollo) - Vue integration for apollo. :star:1847
* [graphql-thinky](https://github.com/fenos/graphql-thinky) - Build an optimized GraphQL schema from Thinky RethinkDB models. :star:65
* [graphql-pouch](https://github.com/MikeBild/graphql-pouch) - A GraphQL-API runtime on top of PouchDB created by GraphQL shorthand notation as a self contained service with CouchDB synchronization. :star:144
* [gql-tools](https://github.com/almilo/gql-tools) - Tool library with CLI for schema generation and manipulation. :star:15
* [graphql-iso-date](https://github.com/excitement-engineer/graphql-iso-date) - A GraphQL date scalar type to be used with GraphQL.js. This scalar represents a date in the ISO 8601 format YYYY-MM-DD. :star:157
* [graphql-compose](https://github.com/nodkz/graphql-compose) - Tool which allows you to construct flexible graphql schema from different data sources via plugins. :star:307
* [node-graphjoiner](https://github.com/mwilliamson/node-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise. :star:39
