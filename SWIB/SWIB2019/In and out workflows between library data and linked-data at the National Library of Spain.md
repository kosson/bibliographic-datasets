---
alias: SWIB
type: presentation
event: SWIB 2019
year: "2019"
partof: "LD in National Libraries"
tags:
  - "#datos"
  - "#linked/data"
  - "#FRBR"
  - "#Wikidata"
  - "#authority/records"
  - "#VIAF"
  - "#API"
title: "In and out: workflows between library data and linked-data at the National Library of Spain"
alt: ''
resources:
  - "https: //swib.org/swib19/slides/santos_in-and-out.pdf"
  - "https: //youtu.be/aMncqcDCm6g"
author:
  - Ricardo Santos
abstract: Datos.bne.es is the linked-data based catalogue at the National Library of Spain. It is built upon the MARC21 library records as the main source of data, and transformed into RDF through a pipeline of analysis, defragmentation, and data re-clustering into the FRBR-based data model. On top of this, a new entity-driven “catalogue” is built for the use of general public and for enhanced discovery from search engines. Datos.bne is an experimental development, making room for testing unconventional workflows for metadata production and creation, breaking up the sometimes rigid conventions taking place in national libraries. This presentation will explore some of the most prominent features in this workflows, and discuss pros and cons found along the way, or how this may influence library metadata production in the near future. One of the most recent features has been the massive data ingestion from Wikidata into 80.000-odd person library records, including properties as gender, birth place, occupation, language, field of work or membership. The matching between library records and Wikidata records was made based on Wikidata identifiers present on authority records. These identifiers were initially extracted from VIAF identifiers datadump file and loaded into the library authority records. After that initial massive load, catalogers have been routinely adding more wikidata URIs when available. After a file was extracted from the library authority file, containing BNE Ids and Wikidata IDs, the library technological partner for this venture got the data through the Wikidata API. After extensive quality check-up, massive modifications, and alignment with the library subject terms, the data were succesfully loaded into the library records, and will be processed for its use in the datos platform, closing the feedback circle.
---
# In and out: workflows between library data and linked-data at the National Library of Spain
[[Ricardo Santos]]

Datos.bne.es is the linked-data based catalogue at the [[National Library of Spain]]. It is built upon the MARC21 library records as the main source of data, and transformed into RDF through a pipeline of analysis, defragmentation, and data re-clustering into the FRBR-based data model. On top of this, a new entity-driven “catalogue” is built for the use of general public and for enhanced discovery from search engines. Datos.bne is an experimental development, making room for testing unconventional workflows for metadata production and creation, breaking up the sometimes rigid conventions taking place in national libraries. This presentation will explore some of the most prominent features in this workflows, and discuss pros and cons found along the way, or how this may influence library metadata production in the near future. One of the most recent features has been the massive data ingestion from [[Wikidata]] into 80.000-odd person library records, including properties as gender, birth place, occupation, language, field of work or membership. The matching between library records and Wikidata records was made based on Wikidata identifiers present on authority records. These identifiers were initially extracted from [[VIAF]] identifiers datadump file and loaded into the library authority records. After that initial massive load, catalogers have been routinely adding more wikidata URIs when available. After a file was extracted from the library authority file, containing BNE Ids and Wikidata IDs, the library technological partner for this venture got the data through the Wikidata [[API]].
After extensive quality check-up, massive modifications, and alignment with the library subject terms, the data were succesfully loaded into the library records, and will be processed for its use in the datos platform, closing the feedback circle.
