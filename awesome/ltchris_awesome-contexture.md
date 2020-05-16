# Information comes from [ltchris/awesome-contexture](https://github.com/ltchris/awesome-contexture)
# Awesome Contexture [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> [Contexture](https://github.com/smartprocure/contexture) abstracts queries/filters and results/aggregations from different backing data stores like ElasticSearch and MongoDB.

[<img src="contexture.png" align="center" width="1000">](https://github.com/smartprocure/contexture)

Contexture is a tool for running the Contexture DSL, which is primarily about **abstracting queries/filters** and **results/aggregrations**. Each leaf node in a Contexture Tree can affect other leaf nodes (e.g., acting as a filter) and has results of it's own which are affected by the other nodes. Non leaf nodes describe how leaves relate to each other, e.g. as a boolean join of and/or. Contexture can use different backing data stores such as MongoDB and ElasticSearch.

This page represents a curated list of Contexture websites, libraries, and resources. Our goal is to provide Contexture developers, both new and established, a place to discover and document awesome Contexture resources.

## Contents

- [Websites](#websites)
- [Libraries](#libraries)
- [Documentation](#documentation)
- [Presentations](#presentations)
- [Videos](#videos)

## Websites 

- [contexture-site](https://contexture.site) - Showcase of Contexture searches adapting to diverse datasets such as: car crashes, restaurant locations, COVID-19, SAT scores, school grants, bank failures.
- [contexture-imdb](https://github.com/smartprocure/contexture-imdb) - An example usage of Contexture to present a search interface for an ElasticSearch index of movie records based on IMDB. :star:2
- [GovSpend](https://app.govspend.com/) - A Contexture web-based tool that makes it easy for government agencies to find a product's best price, identify and validate vendors, request quotes and connect with peers.


## Libraries 

- [contexture](https://github.com/smartprocure/contexture) - The core library that exectues the DSL to retrieve data. :star:12
- [contexture-client](https://github.com/smartprocure/contexture-client) - The client library that manages the DSL, allowing for hyper efficient updates running only what is exactly needed.  :star:1
- [contexture-react](https://github.com/smartprocure/contexture-react) - React components for building Contexture interfaces. :star:4
- [grey-vest](https://github.com/smartprocure/grey-vest) - Component library built for contexture-react.
- [contexture-mongo](https://github.com/smartprocure/contexture-mongo) - MongoDB provider for Contexture. :star:1
- [contexture-elasticsearch](https://github.com/smartprocure/contexture-elasticsearch) - Elasticsearch provider for Contexture. :star:1
- [contexture-exports](https://github.com/smartprocure/contexture-export) - A library that extends Contexture by allowing developers to export searches into files or any other target.
- [contexture-api](https://github.com/ltchris/contexture-api) - A simple FeathersJS REST API for Contexture.


## Documentation
- [Contexture Docs](https://docs.contexture.site/) - Documentation of the entire Contexture ecosystem in one place.
- [Contexture React Storybook](https://smartprocure.github.io/contexture-react) - Contexture React components documentation and examples.
- [GreyVest Storybook](https://smartprocure.github.io/grey-vest) - GreyVest component library's documentation and examples.
- [Contexture](https://github.com/smartprocure/contexture#example-usage) - Documentation on Contexture's core concepts, example usage, and implementation details. :star:12
- [Contexture Client](https://github.com/smartprocure/contexture-client#overview) - Documentation overview of the Contexture Client's features, api, and implementation details. :star:1
- [Contexture ElasticSearch](https://github.com/smartprocure/contexture-elasticsearch#usage) - Usage and API documentation for the Contexture ElasticSearch provider library. :star:1
- [Contexture MongoDB](https://github.com/smartprocure/contexture-mongo#overview) - Usage and API documentation for the Contexture MongoDB provider library. :star:1
- [Contexture Exports](https://github.com/smartprocure/contexture-export#index) - Core concepts and usage documentation for the Contexture Exports library.


## Presentations
- [contexture-ec18-talk](https://github.com/smartprocure/contexture-ec18-talk) - Elasticon 2018 talk About Contexture. :star:2
- [DataContexts talk](https://github.com/smartprocure/dc-talk) - Older presentation on DataContexts, the precursor to contexture-client.


## Videos
- [Contexture Talk (raw)](https://www.youtube.com/watch?v=H1i0SdKLHWc) - This is a raw, unedited version of the talk about Contexture, a toolset for building highly interactive data exploration (aka search) interfaces at the 2018 South Florida Code Camp.
- [Contexture Talk (screen)](https://youtu.be/ZsXVcHWZwWI) - This is a raw, unedited version of the talk about Contexture. This version only shows the screencast.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


