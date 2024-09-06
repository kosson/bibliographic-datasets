---
alias: SWIB
type: presentation
event: SWIB 2020
year: "2020"
partof: "Authorities"
tags:
  - "#Finto"
  - "#controlled/vocabularies"
  - "#indexing"
  - "#subject"
  - "#SKOS"
  - "#YSO"
  - "#vocabulary"
  - "#KOKO"
title: Automated tools for propagating a common hierarchy from a set of vocabularies
alt: ''
resources:
  - "https: //swib.org/swib20/slides/03-06-takala.pdf"
  - 'https: //youtu.be/aFQfLIWHC4c'
author:
  - Joeli Takala
abstract: Through finto.fi the National Library of Finland publishes controlled vocabularies for subject indexing and linking data. Linked Open Data formats such as SKOS, also enable us to combine several vocabularies into a common repository of concepts from various sources. The purpose is to expand one general-purpose vocabulary with others of more specific fields of knowledge in a way that enables us to cover a wider context with one vocabulary. The problem is in assessing and ensuring the interoperability of each vocabulary when used in this manner. The combined data set consists of the Finnish General Upper Ontology (YSO) and fifteen domain-specific controlled vocabularies published in SKOS format. Each vocabulary broadly follows the same data model, with each sharing the upper hierarchy of YSO. In total this amounts to 2.1M triples which are combined into 57k unique concepts and 246k labels in a single common vocabulary, KOKO. The tool used for creating the combined vocabulary is a twelve-step algorithm which is combined with the tools for change-tracking and automated quality assessment in order to publish a common vocabulary of consistent quality. The difficulties arise from recognising the common error types in the data structure of a single vocabulary which would not look alarming on their own, but would create complex dynamics if the vocabularies were combined and different error types cascaded on top of each other. The end result may seem confusing for a user and should be avoided whenever possible. Apart from assessing whether such mistakes exist in the data, we also need to address data synchronisation problems when concepts from one vocabulary are shifted in the hierarchy, removed altogether or split into several new concepts of similar meaning. To achieve this, the update process of each of the vocabularies is synchronised with the updates of the YSO’s hierarchy.
---
# Automated tools for propagating a common hierarchy from a set of vocabularies
[[Joeli Takala]]

Through finto.fi the National Library of Finland publishes controlled vocabularies for subject indexing and linking data. Linked Open Data formats such as [[ACRONYMS/SKOS]], also enable us to combine several vocabularies into a common repository of concepts from various sources. The purpose is to expand one general-purpose vocabulary with others of more specific fields of knowledge in a way that enables us to cover a wider context with one vocabulary. The problem is in assessing and ensuring the interoperability of each vocabulary when used in this manner. The combined data set consists of the Finnish General Upper Ontology ([[YSO]]) and fifteen domain-specific controlled vocabularies published in SKOS format. Each vocabulary broadly follows the same data model, with each sharing the upper hierarchy of YSO. In total this amounts to 2.1M triples which are combined into 57k unique concepts and 246k labels in a single common vocabulary, [[KOKO]]. The tool used for creating the combined vocabulary is a twelve-step algorithm which is combined with the tools for change-tracking and automated quality assessment in order to publish a common vocabulary of consistent quality. The difficulties arise from recognising the common error types in the data structure of a single vocabulary which would not look alarming on their own, but would create complex dynamics if the vocabularies were combined and different error types cascaded on top of each other. The end result may seem confusing for a user and should be avoided whenever possible. Apart from assessing whether such mistakes exist in the data, we also need to address data synchronisation problems when concepts from one vocabulary are shifted in the hierarchy, removed altogether or split into several new concepts of similar meaning. To achieve this, the update process of each of the vocabularies is synchronised with the updates of the YSO’s hierarchy.
