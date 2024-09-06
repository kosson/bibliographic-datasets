---
alias: SWIB
type: presentation
event: SWIB 2015
year: '2015'
partof: 'Opening'
tags:
  - '#vocabulary'
  - '#rdf/data/cube'
  - '#RDF'
  - '#TEI'
  - '#data/cube'
  - '#transformations'
title: Data-Transformation on Historical Data Using the RDF Data Cube Vocabulary
alt: ''
resources:
  - 'https: //swib.org/swib15/slides/bayerl_data-transformation.pdf'
  - 'https: //youtu.be/MWZNRBwpnkY?list=PL7fMsenbLiQ0eKJtpz3NCv0937HPwbWqV'
author:
  - Sebastian Bayerl
  - Michael Granitzer
abstract: 'This work describes how XML-based TEI documents, containing statistical data, can be normalized, converted and enriched using the RDF Data Cube Vocabulary. In particular we focus on a statistical real world data set, namely the statistics of the German Reich around the year 1880, which are available in the TEI format. The data is embedded in complex structured tables, which are relatively easy to understand for humans but they are not suitable for automated processing and data analysis, without heavy pre-processing, due to their varying structural properties and differing table layouts. Therefore, the complex structured tables must be validated, modified and transformed, until they are suitable for the standardized multi-dimensional data structure - the data cube. This work especially focuses on the transformations necessary to normalize the structure of the tables. Performing validation- and cleaning-steps, resolving row- and column-spans and reordering slices are available transformations among multiple others. By combining existing transformations, compound operators are implemented, which can handle specific and complex problems. The identification of structural similarities or properties can be used to automatically suggest sequences of transformations. A second focus is on the advantages, which come by using the RDF Data Cube Vocabulary. Also, a research prototype was implemented to execute the workflow and convert the statistical data into data cubes.'
---
# Data-Transformation on Historical Data Using the RDF Data Cube Vocabulary
[[Sebastian Bayerl]], [[Michael Granitzer]]

This work describes how XML-based [[TEI]] documents, containing statistical data, can be normalized, converted and enriched using the RDF Data Cube Vocabulary. In particular we focus on a statistical real world data set, namely the statistics of the German Reich around the year 1880, which are available in the TEI format. The data is embedded in complex structured tables, which are relatively easy to understand for humans but they are not suitable for automated processing and data analysis, without heavy pre-processing, due to their varying structural properties and differing table layouts. Therefore, the complex structured tables must be validated, modified and transformed, until they are suitable for the standardized multi-dimensional data structure - the data cube. This work especially focuses on the transformations necessary to normalize the structure of the tables. Performing validation- and cleaning-steps, resolving row- and column-spans and reordering slices are available transformations among multiple others. By combining existing transformations, compound operators are implemented, which can handle specific and complex problems. The identification of structural similarities or properties can be used to automatically suggest sequences of transformations. A second focus is on the advantages, which come by using the RDF Data Cube Vocabulary. Also, a research prototype was implemented to execute the workflow and convert the statistical data into data cubes.
