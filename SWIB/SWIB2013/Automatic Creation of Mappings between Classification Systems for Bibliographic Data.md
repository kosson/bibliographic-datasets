---
alias: SWIB
type: presentation
event: SWIB 2013
year: '2013'
partof: 'Mappings and Mashups'
tags:
  - '#classification'
  - '#classification/systems'
  - '#CultureGraph'
  - '#mappings'
  - '#linked/data'
  - '#co-occurrence'
  - '#clustering'
title: Automatic Creation of Mappings between Classification Systems for Bibliographic Data
alt: ''
resources:
  - 'https: //swib.org/swib13/slides/pfeffer_swib13_121.pdf'
  - 'http: //www.scivee.tv/node/61557'
author:
  - Magnus Pfeffer
abstract: 'Classification systems are an important means to provide topic-based access to large collections. Most library collections, however, are often only partially classified and use local or regional classification systems. Traditionally, manually created mappings between classification systems are used to improve this situation. I propose a different approach to automatically create such mappings: To achieve a large base for the mapping algorithm, bibliographic data from diverse sources that contain items classified by the classification systems is aggregated in a single database. Next, a clustering algorithm is used in order to group individual issues and editions of the same work. The basic idea is that for classification purposes, there is no significant difference across editions. Indexing information can thus be consolidated within the clusters, resulting in a higher proportion of dual-indexed entries. The novel step is that instead of individual catalogue entries, the "work-level" clusters are used for an instance-based matching: Statistical analysis creates a co-occurrence table of pairs of classes and high co-occurance of a given pair indicating a match between the two classification systems. This information is aggregated into a complete mapping The approach is implemented on an open-source infrastructure which was mainly developed by the German National Library: CultureGraph.org. In ongoing projects, mappings between several classification systems are being produced. The talk will discuss the approach, the implementation issues and the preliminary results as well as the challenges of publishing the created mappings as linked data.'
---
# Automatic Creation of Mappings between Classification Systems for Bibliographic Data

[[Magnus Pfeffer]]

Classification systems are an important means to provide topic-based access to large collections. Most library collections, however, are often only partially classified and use local or regional classification systems. Traditionally, manually created mappings between [[classification]] systems are used to improve this situation. I propose a different approach to automatically create such mappings: To achieve a large base for the mapping algorithm, bibliographic data from diverse sources that contain items classified by the classification systems is aggregated in a single database. Next, a [[clustering algorithm]] is used in order to group individual issues and editions of the same work. The basic idea is that for classification purposes, there is no significant difference across editions. Indexing information can thus be consolidated within the clusters, resulting in a higher proportion of dual-indexed entries. The novel step is that instead of individual catalogue entries, the “work-level” clusters are used for an instance-based matching: Statistical analysis creates a [[co-occurrence]] table of pairs of classes and high co-occurance of a given pair indicating a match between the two classification systems. This information is aggregated into a complete mapping The approach is implemented on an open-source infrastructure which was mainly developed by the German National Library: [[CultureGraph]].org. In ongoing projects, mappings between several classification systems are being produced. The talk will discuss the approach, the implementation issues and the preliminary results as well as the challenges of publishing the created [[mappings]] as linked data.
