---
alias: SWIB
type: presentation
event: SWIB 2013
year: '2013'
partof: 'Base Technology: The Web'
tags:
  - '#LODLAM'
  - '#knowledge/graph'
  - '#hbz'
  - '#LOD'
  - '#API'
  - '#JSON-LD'
  - '#use/cases'
  - '#Metafacture'
  - '#Elasticsearch'
title: 'From Strings to Things: A Linked Open Data API for Library Hackers and Web Developers'
alt: ''
resources:
 - 'https://swib.org/swib13/slides/steeg_swib13_110.pdf'
 - 'http://www.scivee.tv/node/61578'
author:
  - Fabian Steeg
  - Pascal Christoph
abstract: '"Things, not strings" is a popular slogan pushed by Google in the context of its knowledge graph. The LODLAM community advocates this idea, in particular in the context of authority data. However, if we want users to catalog and search things, not strings, we need to make it easy to go from strings to things. At hbz, we are working on a LOD API in order to allow this for title and authority data - currently for the hbz union catalog (lobid-resources), the German ISIL registry (lobid-organisations), and the German integrated authority file (GND). The API serves JSON-LD over HTTP. JSON-LD is an attempt to make LOD more accessible to web developers who are not familiar with semantic web concepts. Providing a common HTTP API instead of a SPARQL endpoint or RDF dumps serves the same purpose: to make the data and advantages of LOD available to all web developers, and not to semantic web experts only. In this talk, we will present use cases for the API (like an auto-suggest functionality for authority data), and describe our implementation and the technology stack we use: metadata transformation to N-Triples with the Culturegraph Metafacture toolkit, enrichment and conversion of N-Triples to JSON-LD with Hadoop, indexing JSON-LD with Elasticsearch, and building a web API with the Play framework.'
---
# From Strings to Things: A Linked Open Data API for Library Hackers and Web Developers

[[Fabian Steeg]], [[Pascal Christoph]]

“Things, not strings” is a popular slogan pushed by Google in the context of its [[knowledge graph]]. The [[LODLAM]] community advocates this idea, in particular in the context of authority data. However, if we want users to catalog and search things, not strings, we need to make it easy to go from strings to things. At [[hbz]], we are working on a LOD API in order to allow this for title and authority data - currently for the hbz union catalog (lobid-resources), the German ISIL registry (lobid-organisations), and the German integrated authority file ([[GND]]). The [[API]] serves [[JSON-LD]] over HTTP. JSON-LD is an attempt to make LOD more accessible to web developers who are not familiar with semantic web concepts. Providing a common HTTP API instead of a [[SPARQL]] endpoint or RDF dumps serves the same purpose: to make the data and advantages of LOD available to all web developers, and not to semantic web experts only. In this talk, we will present [[use cases]] for the API (like an auto-suggest functionality for authority data), and describe our implementation and the technology stack we use: metadata transformation to N-Triples with the [[Culturegraph]] [[Metafacture]] toolkit, enrichment and conversion of N-Triples to JSON-LD with [[Hadoop]], indexing JSON-LD with [[Elasticsearch]], and building a web API with the Play framework.
