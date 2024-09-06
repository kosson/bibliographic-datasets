---
alias: SWIB
type: 'presentation'
event: Semantic Web in Libraries
year: 2023
partof: 'Authorities'
tags:
  - '#Dutch/Digital/Heritage/Network'
  - '#linked/data'
  - '#digital/heritage'
  - '#Network/of/Terms'
  - '#Comunica/framework'
  - '#SKOS'
  - '#GraphQL/API'
  - '#API'
  - '#OpenRefine'
title: 'Network of Terms: bringing links to your data'
alt: ''
resources:
  - 'https: //swib.org/swib23/slides/04_Enno%20Meijers_SWIB2023%20Network-of-Terms.pdf'
  - 'https: //youtu.be/k3pyIoI2-rI'
author:
  - Enno Meijers
abstract: "How can you find information in heterogeneous linked data sources, available at different locations and managed by different owners? At the\_[Dutch Digital Heritage Network](https://netwerkdigitaalerfgoed.nl/)\_we developed a federated querying service to solve this problem:\_[the Network of Terms](https://termennetwerk.netwerkdigitaalerfgoed.nl/). We encourage cultural institutions to publish their data as Linked Data and assign standardized terms to their digital heritage information. Terms are standardized descriptions of concepts or entities that make heritage easier to find for anyone interested in it. Yet it is quite a challenge for institutions to use these terms, because the sources in which the terms are managed – such as thesauri and reference lists – have different API protocols and data models."
---
# Network of Terms: bringing links to your data
[[Enno Meijers]]

How can you find information in heterogeneous linked data sources, available at different locations and managed by different owners? At the <a href="https://netwerkdigitaalerfgoed.nl/">Dutch Digital Heritage Network</a> we developed a federated querying service to solve this problem: <a href="https://termennetwerk.netwerkdigitaalerfgoed.nl/">the Network of Terms</a>. We encourage cultural institutions to publish their data as Linked Data and assign standardized terms to their digital heritage information. Terms are standardized descriptions of concepts or entities that make heritage easier to find for anyone interested in it. Yet it is quite a challenge for institutions to use these terms, because the sources in which the terms are managed – such as thesauri and reference lists – have different API protocols and data models.
The Network of Terms removes these barriers. It is a service that searches linked data sources in a federative way using the <a href="https://comunica.dev/">Comunica framework</a>. It has a unified SKOS based on GraphQL API that can be easily implemented in collection registration or other systems. It searches the sources for matching terms – real time, with SPARQL. The Network of Terms is published as <a href="https://github.com/netwerk-digitaal-erfgoed/network-of-terms">open source</a> and its API is already integrated in five commercial systems and one open source system for collection registration. It also provides a reconcilation API for use in OpenRefine and other tools. The Network of Terms has been already adopted widely in the cultural heritage domain in the Netherlands but we think it has potential for use in other countries and domains too and we would like to present our tool for the SWIB audience.
