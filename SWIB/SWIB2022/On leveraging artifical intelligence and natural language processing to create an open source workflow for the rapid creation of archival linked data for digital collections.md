---
alias: SWIB
type: presentation
event: SWIB 2022
year: "2022"
partof: "Linked Library Data II"
tags:
  - "#AI"
  - "#HIVE2"
  - "#OpenRefine"
title: On leveraging artificial intelligence and natural language processing to create an open source workflow for the rapid creation of archival linked data for digital collections
alt: ''
resources:
  - "https: //swib.org/swib22/slides/Proctor_swib22.pdf"
  - "https: //youtu.be/sI_oumTT-ew"
author:
  - Jennifer Erin Proctor
abstract: This paper proposes, tests, and evaluates an Artificial-Intelligence-supported workflow to enhance the ability of librarians and archivists to convert standardized metadata to better-than-item-level archival linked data. The protocol combines elements of computer vision with natural language processing, entity extraction, and metadata linking techniques to provide new approaches for findability and usability of cultural resources in digital spaces. Existing metadata and, optionally, images are taken as input. Metadata text is processed with natural language processing including sentenizing, tokenizing, part-of-speech tagging, chunking of phrases and clauses, and finally named entity recognition, extraction, and linking. Entities are used to query HIVE2, a search tool that matches ontology terms to linked data tags, which are then parsed into triples through semantic processing. For images, each image is processed to identify people who are pictured in it. Cropped sub-images are created for each person where each image is given a unique identifier to act as its primary linked data entity, and a first triple is created showing that that entity is depicted in the image being processed. Once the spreadsheet of triples is output, it can be imported into OpenRefine in order to convert it into the Wikidata format which is useful for linked digital collections, crowdsourcing, and cooperative collections-as-data programs.
---
# On leveraging artificial intelligence and natural language processing to create an open source workflow for the rapid creation of archival linked data for digital collections
[[Jennifer Erin Proctor]]

This paper proposes, tests, and evaluates an Artificial-Intelligence-supported workflow to enhance the ability of librarians and archivists to convert standardized metadata to better-than-item-level archival linked data. The protocol combines elements of computer vision with natural language processing, entity extraction, and metadata linking techniques to provide new approaches for findability and usability of cultural resources in digital spaces. Existing metadata and, optionally, images are taken as input. Metadata text is processed with natural language processing including sentenizing, tokenizing, part-of-speech tagging, chunking of phrases and clauses, and finally named entity recognition, extraction, and linking. Entities are used to query [[HIVE2]], a search tool that matches ontology terms to linked data tags, which are then parsed into triples through semantic processing. For images, each image is processed to identify people who are pictured in it. Cropped sub-images are created for each person where each image is given a unique identifier to act as its primary linked data entity, and a first triple is created showing that that entity is depicted in the image being processed. Once the spreadsheet of triples is output, it can be imported into [[SOFTWARE/OpenRefine]] in order to convert it into the Wikidata format which is useful for linked digital collections, crowdsourcing, and cooperative collections-as-data programs.
