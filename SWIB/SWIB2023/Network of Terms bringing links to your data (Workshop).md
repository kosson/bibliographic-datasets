---
alias: SWIB
type: 'workshop'
event: Semantic Web in Libraries
year: 2023
partof: 'Workshops'
tags:
  - '#network/of/terms'
  - '#linked/data'
  - '#Dutch/Digital/Heritage/Network'
  - '#SKOS'
  - '#GraphQL/API'
  - '#Comunica/framework'
  - '#API'
  - '#SPARQL'
title: 'Network of Terms: bringing links to your data (Workshop)'
alt: ''
resources:
  - ''
author:
  - Enno Meijers
  - Bob Coret
abstract: "How can you find information in heterogeneous Linked Data sources, available at different locations and managed by different owners? At the\_[Dutch Digital Heritage Network](https://netwerkdigitaalerfgoed.nl/)\_we developed a federated querying service to solve this problem:\_[the Network of Terms](https://termennetwerk.netwerkdigitaalerfgoed.nl/). We encourage cultural institutions to publish their data as Linked Data and assign standardized terms to their digital heritage information. Terms are standardized descriptions of concepts or entities that make heritage easier to find for anyone interested in it. Yet it is quite a challenge for institutions to use these terms, because the sources in which the terms are managed – such as thesauri and reference lists – have different API protocols and data models. The Network of Terms removes these barriers. It is a service that searches Linked Data sources in a federative way using the\_[Comunica framework](https://comunica.dev/). It has a unified SKOS based on GraphQL API that can be easily implemented in collection registration or other systems. It searches the sources for matching terms – real time, with SPARQL. The Network of Terms is published as\_[open source](https://github.com/netwerk-digitaal-erfgoed/network-of-terms)\_and its API is already integrated in five commercial systems and one open source system for collection registration. It also provides a Reconcilation API for use in Openrefine and other tools."
---
# Network of Terms: bringing links to your data (Workshop)
[[Enno Meijers]], [[Bob Coret]]

How can you find information in heterogeneous Linked Data sources, available at different locations and managed by different owners? At the <a href="https://netwerkdigitaalerfgoed.nl/">Dutch Digital Heritage Network</a> we developed a federated querying service to solve this problem: <a href="https://termennetwerk.netwerkdigitaalerfgoed.nl/">the Network of Terms</a>. We encourage cultural institutions to publish their data as Linked Data and assign standardized terms to their digital heritage information. Terms are standardized descriptions of concepts or entities that make heritage easier to find for anyone interested in it. Yet it is quite a challenge for institutions to use these terms, because the sources in which the terms are managed – such as thesauri and reference lists – have different API protocols and data models. The Network of Terms removes these barriers. It is a service that searches Linked Data sources in a federative way using the <a href="https://comunica.dev/">Comunica framework</a>. It has a unified SKOS based on GraphQL API that can be easily implemented in collection registration or other systems. It searches the sources for matching terms – real time, with SPARQL. The Network of Terms is published as <a href="https://github.com/netwerk-digitaal-erfgoed/network-of-terms">open source</a> and its API is already integrated in five commercial systems and one open source system for collection registration. It also provides a Reconcilation API for use in Openrefine and other tools.
Although the core of the software is written in Typescript, the configuration for adding terminology sources through a so-called catalogue requires only basic knowledge of JSON and SPARQL. For testing purposes local instances can be easily set up in Node.js compliant environments. In this workshop we demonstrate the functionality and work with participants to build their specific catalogue using the terminology sources of their preference.
