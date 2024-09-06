---
alias: SWIB
type: lighning talk
event: SWIB 2022
year: "2022"
partof: "RDF Insights / Lightning Talks"
tags:
  - "#Japanese/Visual/Media/Graph"
  - "#project"
  - "#jvmg"
  - "#knowledge/graph"
  - "#triplestore"
  - "#SPARQL"
  - "#Blazegraph"
  - "#Virtuoso"
  - "#GraphDB"
  - "#co-occurrence"
  - "#discrepancies"
title: Performance comparison of select and construct queries of triplestores on the example of the JVMG project
alt: ''
resources:
  - "https: //swib.org/swib22/slides/SWIB_malmsheimer.pdf"
author:
  - Tobias Malmsheimer
abstract: |-
  In the Japanese Visual Media Graph (JVMG) project ([Project blog](https://jvmg.iuk.hdm-stuttgart.de/), [JVMG web frontend (Beta)](https://mediagraph.link/)) we use the Resource Description Framework (RDF) to create a knowledge graph for researchers working with contemporary popular Japanese media. The project is funded by the German Research Foundation and the main project partners are Stuttgart Media University and Leipzig University Library.
  In order to easily access our RDF data we use a triplestore and SPARQL. We initially chose the Apache Fuseki triple store because of its open licensing terms and ease of installation and management.
  Once the database was completed to a certain degree, we implemented and tested our knowledge graph using different triplestore software solutions (Apache Fuseki, Blazegraph, Virtuoso and GraphDB) and compared their performance on several tasks that we consider representative operations on our data. These tasks include simple queries such as aggregating all data for a given entity and more complex analyses such as finding co-occurrence. We found major performance discrepancies, both between the different software solutions and between SELECT and CONSTRUCT SPARQL queries. Query times differ by factors of up to 100 across the software solutions, and CONSTRUCT queries consistently perform much worse, even when using the exact same WHERE patterns.
  In summary, the Apache Fuseki triple store performed quite well across all tasks. While some other software solutions were faster for some tasks, the gains were not significant enough to consider migrating our infrastructure to a new solution.
---
# Performance comparison of select and construct queries of triplestores on the example of the JVMG project
[[Tobias Malmsheimer]]

In the [[Japanese Visual Media Graph]] ([[JVMG]]) [[project]] (<a href="https://jvmg.iuk.hdm-stuttgart.de/">Project blog</a>, <a href="https://mediagraph.link/">JVMG web frontend (Beta)</a>) we use the Resource Description Framework ([[RDF]]) to create a knowledge graph for researchers working with contemporary popular Japanese media. The project is funded by the [[German Research Foundation]] and the main project partners are [[Stuttgart Media University]] and [[Leipzig University Library]]. In order to easily access our RDF data we use a [[triplestore]] and [[SPARQL]]. We initially chose the [[Apache Fuseki]] triple store because of its open licensing terms and ease of installation and management. Once the database was completed to a certain degree, we implemented and tested our knowledge graph using different triplestore software solutions (Apache Fuseki, [[Blazegraph]], [[Virtuoso]] and [[GraphDB]]) and compared their performance on several tasks that we consider representative operations on our data. These tasks include simple queries such as aggregating all data for a given entity and more complex analyses such as finding [[co-occurrence]]. We found major performance discrepancies, both between the different software solutions and between SELECT and CONSTRUCT SPARQL queries. Query times differ by factors of up to 100 across the software solutions, and CONSTRUCT queries consistently perform much worse, even when using the exact same WHERE patterns. In summary, the Apache Fuseki triple store performed quite well across all tasks. While some other software solutions were faster for some tasks, the gains were not significant enough to consider migrating our infrastructure to a new solution.
