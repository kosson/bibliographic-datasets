---
alias: SWIB
type: presentation
event: SWIB 2012
year: '2012'
partof: ''
tags:
  - '#norway'
  - '#frbr'
  - '#frbr/clustering'
  - '#authority/file'
  - '#API'
  - '#Oslo'
title: 'The Library Catalogue as Linked Open Data : How to Do It and What to Do with It'
alt: ''
resources:
  - https://swib.org/swib12/slides/Rekkavik_SWIB12_110.pdf
  - http://www.scivee.tv/node/55304
author:
  - Asgeir Rekkavik
  - Benjamin Rokseth
abstract: |-
  Oslo Public Library has developed an open source toolkit for producing an RDF representation of the library catalogue and its authority files. In addition to plain conversion of MARC bibliographic data into RDF, the current implementation includes SPARQL methods for FRBR clustering of the library collection, as well as enriching catalogue data with external content, such as cover images and book reviews, from various APIs and Linked Open Data sources.
  During the first half of 2012, Oslo Public Library has run two simultaneous projects that demonstrate and take advantage of some of the possibilities an enriched RDF representation of the library catalogue might provide. This has resulted in two working open source service prototypes:
---
# The Library Catalogue as Linked Open Data : How to Do It and What to Do with It

[[Asgeir Rekkavik]], [[Benjamin Rokseth]]

[[Oslo Public Library]] has developed an open source toolkit for producing an [[RDF]] representation of the library catalogue and its authority files. In addition to plain conversion of MARC bibliographic data into RDF, the current implementation includes [[SPARQL]] methods for [[FRBR]] clustering of the library collection, as well as enriching catalogue data with external content, such as cover images and book reviews, from various [[APIs]] and Linked Open Data sources.
During the first half of 2012, [[Oslo]] Public Library has run two simultaneous projects that demonstrate and take advantage of some of the possibilities an enriched RDF representation of the library catalogue might provide. This has resulted in two working open source service prototypes:

- Book Reviews. Librarians produce lots of book reviews, a valuable resource that regrettably is often poorly exploited. The Book Reviews prototype is a web application, designed to collect, register and distribute library produced book reviews, as well as linking them to the library catalogue and making them easily accessible for use in other web applications.
- Active Shelves. The active shelf is a physical touch-screen device that makes use of open source software, RFID technology, RDF data and external web service APIs to provide information about any book a library patron is curious to know more about, as well as suggesting other titles that might spur the user’s interest.

