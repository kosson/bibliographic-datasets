---
alias: SWIB
type: 'presentation'
event: Semantic Web in Libraries
year: 2023
partof: 'Authorities'
tags:
  - '#LD4P'
  - '#Cornell/University/Library'
  - '#API'
  - '#linked/data'
  - '#Linked/Data/For/Production'
  - '#Sinopia'
  - '#RDF'
title: Supporting sustainable lookup services
alt: ''
resources:
  - 'https: //swib.org/swib23/slides/03_Steven%20Folsom_Supporting%20Sustainable%20Lookup%20Services.pdf'
  - 'https: //youtu.be/bdpMAoq3hIs'
author:
  - Steven Folsom
abstract: "As presented at previous SWIB conferences, the\_[LD4P Authority Lookup Service](https://lookup.ld4l.org/), maintained by Cornell University Library, is designed to be a translation layer that provides an easily consumable normalized API response when searching across multiple authority data sources.\nThis presentation will reflect on [Linked Data For Production] (https://wiki.lyrasis.org/display/LD4P3)’s recent efforts to more sustainably support lookups in Sinopia (an RDF cataloguing tool,\_[https://sinopia.io/](https://sinopia.io/)), and share what we have learned about the requirements for robust lookup services. We will describe the opportunities and challenges of relying on caching for lookups, and explain how the significant maintenance costs associated with caching a large number of authorities led us to a no-cache approach, where we instead translate existing authority search APIs into a normalized response. We maintain hope that cache-based lookup services will be feasible for vendors and consortia to support. To this end, and based on the persistent challenge we faced with keeping cached data current, this talk will also describe an\_[API specification](https://github.com/LD4/entity_metadata_management)\_we are developing to as a possible way to standardize how data providers communicate changes to their data more frequently than periodic data dumps."
---
# Supporting sustainable lookup services
[[Steven Folsom]]

As presented at previous SWIB conferences, the <a href="https://lookup.ld4l.org/">LD4P Authority Lookup Service</a>, maintained by Cornell University Library, is designed to be a translation layer that provides an easily consumable normalized API response when searching across multiple authority data sources.
This presentation will reflect on [Linked Data For Production] (https://wiki.lyrasis.org/display/LD4P3)’s recent efforts to more sustainably support lookups in Sinopia (an RDF cataloguing tool, <a href="https://sinopia.io/">https://sinopia.io/</a>), and share what we have learned about the requirements for robust lookup services. We will describe the opportunities and challenges of relying on caching for lookups, and explain how the significant maintenance costs associated with caching a large number of authorities led us to a no-cache approach, where we instead translate existing authority search APIs into a normalized response. We maintain hope that cache-based lookup services will be feasible for vendors and consortia to support. To this end, and based on the persistent challenge we faced with keeping cached data current, this talk will also describe an <a href="https://github.com/LD4/entity_metadata_management">API specification</a> we are developing to as a possible way to standardize how data providers communicate changes to their data more frequently than periodic data dumps.
