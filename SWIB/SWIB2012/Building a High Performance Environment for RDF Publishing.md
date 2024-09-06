---
alias: SWIB
type: presentation
event: SWIB 2012
year: 2012
partof: ''
tags:
  - '#sparql/performance'
  - '#performance'
  - '#sparql'
  - '#elasticsearch'
  - '#indexing'
  - '#lobid'
  - '#4store'
  - '#triplestore'
  - '#content/negotiation'
  - '#linked/open/data'
  - '#triple/store'
  - '#SPARQL'
  - '#JSON-LD'
title: Building a High Performance Environment for RDF Publishing
alt: ''
resources:
  - https://swib.org/swib12/slides/Christoph_SWIB12_117.pdf
  - http://www.scivee.tv/node/55329
author:
  - Pascal Christoph
abstract: Linked Open Data can be published in different forms (flat files, RDFa, triple store). In lobid we used an approach centered around a triple store (4store). Different RDF-serializations of resources (turtle, RDF/XML, RDFa-enriched HTML presentations etc.) are generated through SPARQL queries and provided via content negotiation. Running a triple store and providing a SPARQL endpoint allows powerful queries to make the best out of LOD. But then, these queries often take their time, especially if you have a large data pool. While it is possible doing string searches via SPARQL, we found that it is not really performant dealing with lots of data, and language processing is not supported at all. Thus, we are running a search engine (elasticsearch) alongside the triple store to enable fast string searches. This talk is about indexing of data into the triple store and into the search engine in parallel to reap even more benefits from elasticsearch. As elasticsearch indexes data using JSON, this approach makes use of JSON-LD, a JSON serialization for RDF. elasticsearch comes with many features that we are looking for using with our LOD anyway - like high availability, distributed index, near-realtime updates, versioning and fast geo-searching. The talk will highlight how these benefits can be used for LOD.
---
# Building a High Performance Environment for RDF Publishing
[[Pascal Christoph]]

Linked Open Data can be published in different forms (flat files, RDFa, triple store). In [[lobid]] we used an approach centered around a triple store ([[4store]]). Different RDF-serializations of resources (turtle, RDF/XML, RDFa-enriched HTML presentations etc.) are generated through [[SPARQL]] queries and provided via content negotiation. Running a triple store and providing a SPARQL endpoint allows powerful queries to make the best out of LOD. But then, these queries often take their time, especially if you have a large data pool. While it is possible doing string searches via SPARQL, we found that it is not really performant dealing with lots of data, and language processing is not supported at all. Thus, we are running a search engine ([[elasticsearch]]) alongside the triple store to enable fast string searches. This talk is about indexing of data into the triple store and into the search engine in parallel to reap even more benefits from elasticsearch. As elasticsearch indexes data using JSON, this approach makes use of JSON-LD, a JSON serialization for RDF. elasticsearch comes with many features that we are looking for using with our LOD anyway - like high availability, distributed index, near-realtime updates, versioning and fast geo-searching. The talk will highlight how these benefits can be used for [[LOD]].
