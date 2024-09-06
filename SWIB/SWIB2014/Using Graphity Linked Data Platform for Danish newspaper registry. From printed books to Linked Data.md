---
alias: SWIB
type: presentation
event: SWIB 2014
year: '2014'
partof: 'LOD Applications'
tags:
  - '#denmark'
  - '#newspapers'
  - '#TEI'
  - '#Dydra'
  - '#XHTML'
  - '#XSLT'
title: Using Graphity Linked Data Platform for Danish newspaper registry. From printed books to Linked Data
alt: ''
resources:
  - 'https: //swib.org/swib14/slides/tornau_swib14_22.pdf'
  - 'http: //www.scivee.tv/node/63274'
author:
  - Martynas Jusevicius
  - Dziugas Tornau
abstract: 'Danish Newspapers is a registry of newspapers with historical and factual metadata records. Three printed volumes with metadata about danish newspaper publishing were scanned and text optically recognized, marking it up using TEI XML schema. The XML was converted into XML-based RDF quad format using multiple domain-specific vocabularies (SKOS, BIBO, Time ontology etc.) in a custom XSLT stylesheet. Rich non-structured text was preserved as XHTML literals, with links to images stored as JPG files. The data was stored in Dydra cloud triplestore and presented as a Web application that publishes Linked Data as well as user-friendly and mobile-ready XHTML. It features interactive maps, faceted and text search, autocomplete and complex content creation and editing for authenticated users. URI templates, SPARQL queries, data quality constraints and access control were defined declaratively as RDF data and processed in run-time by Graphity platform, while XSLT stylesheets were used to generate a customized XHTML layout and facets. Graphity processor is open-source and works with any SPARQL 1.1 triplestore, while the commercial platform layer provides multi-tenant features such as access control and faceted search. Linking with external datasources and alignment with standard models were not in scope for this project, as the focus was on data conversion, content presentation and data filtering. The data can be mapped to generic bibliographic vocabularies such as BIBFRAME and EDM using SPARQL Update.'
---
# Using Graphity Linked Data Platform for Danish newspaper registry. From printed books to Linked Data

[[Martynas Jusevicius]], [[Dziugas Tornau]]

Danish Newspapers is a registry of newspapers with historical and factual metadata records. Three printed volumes with metadata about danish newspaper publishing were scanned and text optically recognized, marking it up using [[TEI]] XML schema. The XML was converted into XML-based RDF quad format using multiple domain-specific vocabularies ([[ACRONYMS/SKOS]], [[BIBO]], Time ontology etc.) in a custom XSLT stylesheet. Rich non-structured text was preserved as XHTML literals, with links to images stored as JPG files. The data was stored in [[Dydra]] cloud triplestore and presented as a Web application that publishes Linked Data as well as user-friendly and mobile-ready [[XHTML]]. It features interactive maps, faceted and text search, autocomplete and complex content creation and editing for authenticated users. URI templates, [[SPARQL]] queries, data quality constraints and access control were defined declaratively as RDF data and processed in run-time by [[Graphity]] platform, while [[XSLT]] stylesheets were used to generate a customized XHTML layout and facets. Graphity processor is open-source and works with any SPARQL 1.1 triplestore, while the commercial platform layer provides multi-tenant features such as access control and faceted search. Linking with external datasources and alignment with standard models were not in scope for this project, as the focus was on data conversion, content presentation and data filtering. The data can be mapped to generic bibliographic vocabularies such as BIBFRAME and EDM using SPARQL Update.
