---
alias: SWIB
type: presentation
event: SWIB 2012
year: '2012'
partof: ''
tags:
  - '#synchronisation'
  - '#library/metadata'
  - '#metadata'
title: Towards an Infrastructure for the Synchronisation of Metadata in Libraries
alt: ''
resources:
  - https://swib.org/swib12/slides/B%C3%B6hme_SWIB12_113.ppt
  - http://www.scivee.tv/node/55388
author:
  - Christoph Böhme
abstract: With LOD information is represented in a giant distributed graph. This graph is constantly changing and evolving but to date no infrastructure has been established for continuously propagating and tracking the changes of nodes and edges in this graph. In libraries, metadata is traditionally distributed and synchronised using protocols such as Z39.50, SRU or OAI-MPH to poll individual datasets for changes. While this works well when only a small number of datasets exchanges data infrequently, it does not when synchronisation happens continuously and at the scale of the LOD graph. However, users expect that data is always up-to-date. For example, a search index which includes external information about the latest headlines is expected to contain not only last week’s headlines but also today’s. Constant polling for changes can constitute a major performance issue in such scenarios. In our contribution we discuss different synchronisation patterns for library metadata and the requirements for a synchronisation infrastructure arising from them. Of particular importance in this discussion is the fact that subscribers are not always interested in all changes to a dataset but only in those affecting a small set of selected records. Related to this is the aspect that changes of library metadata most of the time only affect single records but sometimes large updates touch whole data sets producing change sets which can consist of millions of records at a time. A synchronisation system must be able to handle these different sized payloads and help participating systems to cope with large change sets. We review existing solutions and outline a future solution for the library domain.
---
# Towards an Infrastructure for the Synchronisation of Metadata in Libraries

[[Christoph Böhme]]

With LOD information is represented in a giant distributed graph. This graph is constantly changing and evolving but to date no infrastructure has been established for continuously propagating and tracking the changes of nodes and edges in this graph. In libraries, metadata is traditionally distributed and synchronised using protocols such as Z39.50, SRU or OAI-MPH to poll individual datasets for changes. While this works well when only a small number of datasets exchanges data infrequently, it does not when synchronisation happens continuously and at the scale of the LOD graph. However, users expect that data is always up-to-date. For example, a search index which includes external information about the latest headlines is expected to contain not only last week’s headlines but also today’s. Constant polling for changes can constitute a major performance issue in such scenarios. In our contribution we discuss different [[synchronisation patterns]] for [[library metadata]] and the requirements for a synchronisation infrastructure arising from them. Of particular importance in this discussion is the fact that subscribers are not always interested in all changes to a dataset but only in those affecting a small set of selected records. Related to this is the aspect that changes of library metadata most of the time only affect single records but sometimes large updates touch whole data sets producing change sets which can consist of millions of records at a time. A synchronisation system must be able to handle these different sized payloads and help participating systems to cope with large change sets. We review existing solutions and outline a future solution for the library domain.
