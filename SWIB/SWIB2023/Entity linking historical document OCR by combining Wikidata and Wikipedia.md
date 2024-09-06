---
alias: SWIB
type: 'presentation'
event: Semantic Web in Libraries
year: 2023
partof: 'Utilizing Wikimedia'
tags:
  - '#named/entities'
  - '#named/entity/recognition'
  - '#knowledge/base'
  - '#entity/linking'
  - '#dirichlet/allocation'
title: Entity linking historical document OCR by combining Wikidata and Wikipedia
alt: ''
resources:
  - 'https: //swib.org/swib23/slides/03_Kai%20Labusch_Clemens%20Neudecker_SWIB23.pdf'
  - 'https: //youtu.be/pGT5xE-jnOY'
author:
  - Kai Labusch
  - Clemens Neudecker
abstract: Named entities like persons, locations and organisations are a prominent target for search in digitized collections. While named entity recognition can be used to automatically detect named entities in texts, through the additional disambiguation and linking of the entities to authority files their usability for retrieval and linking to other sources is significantly improved.
---
# Entity linking historical document OCR by combining Wikidata and Wikipedia
[[Kai Labusch]], [[Clemens Neudecker]]

Named entities like persons, locations and organisations are a prominent target for search in digitized collections. While named entity recognition can be used to automatically detect named entities in texts, through the additional disambiguation and linking of the entities to authority files their usability for retrieval and linking to other sources is significantly improved.
We used Wikidata to construct a comprehensive knowledge-base that holds information on linkable entities and combined it with a Wikipedia-derived corpus of text references that can be used by a neural network-based entity linking system to find references of entities in historical German texts. We demonstrate the feasibility of the approach on ~5,000,000 pages of historical German texts obtained by OCR and show how the entity linking results can be used to group the entire historical text corpus by latent dirichlet allocation. All software components are also released as open source for others to adapt and reuse.