---
alias: SWIB
type: presentation
event: SWIB 2019
year: "2019"
partof: "Exploring new ways"
tags:
  - "#Sweden"
  - "#union/catalogue"
  - "#RDFS"
  - "#OWL"
  - "#reasoners"
  - "#vocabulary"
  - "#XSLT"
  - "#SPARQL"
  - "#vocabulary/map"
  - "#shortcomings"
title: Target vocabulary maps
alt: ''
resources:
  - "https: //swib.org/swib19/slides/08_lindstroem_target-vocabulary-maps.pdf"
  - 'https: //youtu.be/A_1BIDAlbeI'
author:
  - Niklas Lindström
abstract: |
  'The union catalogue of the National Library of Sweden now has a core based on linked data structures. In the course of our continued development we have begun exploring the feasibility of semantic technologies (RDFS and OWL) for more wide and open-ended data integration. OWL inferencing is sometimes considered a foundational mechanism for automatic semantic interoperability. But we need to go about it differently in order for semantic mappings to become a practical tool for effective data integration. OWL reasoners are rarely used when automating ingestion or publication of linked data. Reasoners aren't readily targeted at specific applications, but expand all possible implications of a set of statements, yielding rather unwieldy data. Meanwhile the web of data at large continues to grow, and between organizations more and more integration needs crop up. These needs commonly have to be solved right now, thus requiring us to write up more custom integration code, with little reuse even within one organization. It is not uncommon to device custom mappings between RDF vocabularies as a part of these often complex ETL pipelines. Sometimes, these use SPARQL, sometimes XSLT, sometimes custom code with various non-portable dependencies. We're exploring an arguably simpler approach to address a given set of described use cases. It is based on preprocessing of vocabulary data, scanning their mappings and creating a target map from each known property and class to a predefined selection of desired target properties and classes. This computed "target vocabulary map" is then used when reading input data using the known terms, to produce the selected target description. This yields more predictive results tailored for conceived use cases. This presentation will elaborate on these considerations and explore the proposed solution, including limitations and possible shortcomings.'
---
# Target vocabulary maps
[[Niklas Lindström]]

The union catalogue of the National Library of Sweden now has a core based on linked data structures. In the course of our continued development we have begun exploring the feasibility of semantic technologies ([[RDFS]] and [[OWL]]) for more wide and open-ended data integration. OWL inferencing is sometimes considered a foundational mechanism for automatic semantic interoperability. But we need to go about it differently in order for semantic mappings to become a practical tool for effective data integration. OWL reasoners are rarely used when automating ingestion or publication of linked data. Reasoners aren’t readily targeted at specific applications, but expand all possible implications of a set of statements, yielding rather unwieldy data. Meanwhile the web of data at large continues to grow, and between organizations more and more integration needs crop up. These needs commonly have to be solved right now, thus requiring us to write up more custom integration code, with little reuse even within one organization. It is not uncommon to device custom mappings between RDF vocabularies as a part of these often complex ETL pipelines. Sometimes, these use SPARQL, sometimes XSLT, sometimes custom code with various non-portable dependencies.
We’re exploring an arguably simpler approach to address a given set of described use cases. It is based on preprocessing of vocabulary data, scanning their mappings and creating a target map from each known property and class to a predefined selection of desired target properties and classes. This computed “target vocabulary map” is then used when reading input data using the known terms, to produce the selected target description. This yields more predictive results tailored for conceived use cases.
This presentation will elaborate on these considerations and explore the proposed solution, including limitations and possible shortcomings.
