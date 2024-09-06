---
alias: SWIB
type: presentation
event: SWIB 2018
year: "2018"
partof: "Automating LOD"
tags:
  - "#aggregation"
  - "#data/aggregation"
  - "#transformation"
title: Transformations for aggregating Linked Open Data
alt: ''
resources:
  - "https: //swib.org/swib18/slides/2_mckenna_engaging-information-professionals.pdf"
  - 'https: //youtu.be/HeWgBXaWZYc'
author:
  - Lukas Koster
  - Ivo Zandhuis
abstract: |
  'Linked Open Data is usually provided as-is. Institutions make choices how to model the data, including properties, blank nodes and uris, for valid reasons. If you want to combine data, there are generally two options: 1) do a distributed query and inference on the data 2) aggregate the data into a new, single endpoint. Distribution enables the use of all available data structures, aggregation enables more easy-to-use data and better performance. For aggregation it is good practice to do transformations to obtain the needed convenience. We give an overview of the transformation types needed, learned in the AdamNet Library Association project AdamLink, a collaboration of the Amsterdam City Archives, Amsterdam Museum, University of Amsterdam Library, Public Library of Amsterdam and International Institute of Social History. The objective is to create a linked open data infrastructure connecting the member institutions’ collections on the topic of "Amsterdam", targeted at reuse by researchers, teachers, students, creative industry and general public. We discuss the (dis)advantages of creating an aggregation vs. distribution of queries. Every transformation type should solve a distribution problem to be useful. But transformation probably reduces querying-options on the data. We therefore need to get the best trade-off between complexity and usability. An interesting option to investigate is to apply a caching node mechanism, that could combine the best of both worlds. We distinguish 6 types of transformation: Mapping ontologies - Mapping and adding thesauri and authority lists - Mapping and adding object-types - Adding our own statements - Restructuring data - Data-typing. We will illustrate the transformations with real examples. We will also discuss the issues with feeding back the enriched data in the cache or aggregation to the original data sources.'
---
# Transformations for aggregating Linked Open Data
[[Lukas Koster]], [[Ivo Zandhuis]]

Linked Open Data is usually provided as-is. Institutions make choices how to model the data, including properties, blank nodes and uris, for valid reasons. If you want to [[combine data]], there are generally two options: 1) do a [[distributed query]] and [[inference]] on the data 2) [[aggregate the data]] into a new, single endpoint. Distribution enables the use of all available data structures, aggregation enables more easy-to-use data and better performance. For aggregation it is good practice to do transformations to obtain the needed convenience. We give an overview of the transformation types needed, learned in the [[AdamNet Library Association]] [[project]] [[AdamLink]], a collaboration of the [[Amsterdam City Archives]], [[Amsterdam Museum]], [[University of Amsterdam Library]], [[Public Library of Amsterdam]] and [[International Institute of Social History]]. The objective is to create a [[linked open data]] [[Templates/infrastructure]] connecting the member institutions’ collections on the topic of “Amsterdam”, targeted at reuse by researchers, teachers, students, creative industry and general public. We discuss the (dis)advantages of creating an aggregation vs. distribution of queries. Every transformation type should solve a distribution problem to be useful. But transformation probably reduces querying-options on the data. We therefore need to get the best trade-off between complexity and usability. An interesting option to investigate is to apply a caching node mechanism, that could combine the best of both worlds. We distinguish 6 types of [[transformation]]: Mapping [[ontologies]] - Mapping and adding [[thesauri]] and [[authority lists]] - Mapping and adding [[object-types]] - Adding our [[own statements]] - [[Restructuring data]] - Data-typing. We will illustrate the transformations with real examples. We will also discuss the issues with feeding back the enriched data in the cache or aggregation to the original data sources.
