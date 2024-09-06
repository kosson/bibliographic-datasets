---
alias: SWIB
type: presentation
event: SWIB 2021
year: "2021"
partof: "Tools"
tags:
  - "#SPARQL"
  - "#SparqlExplorer"
title: SparqlExplorer, exploring Linked Open Data
alt: ''
resources:
  - "https: //swib.org/swib21/slides/03-04-thieblin.pdf"
  - 'https: //youtu.be/NXOq-u_1ZJQ'
author:
  - Fabien Amarger
  - Elodie Thieblin
  - Chauvat Nicolas
abstract: 'Since developing and maintaining web applications is costly, a lot of the data published in SPARQL endpoints is difficult to explore by users that are not experts of LOD tools and languages. In order to make that data more accessible we developed SparqlExplorer, a web application that can be plugged into any SPARQL endpoint to make its content browsable without writing a single query by applying views to render web pages. For example, to explore a dataset about books, SparqlExplorer would use a book-specific views that executes a SPARQL query to retrieve that data related to a book and generate a web page that displays the title, the ISBN and maybe a thumbnail of the cover. Views are javascript functions that take data and output HTML. Views depend on the structure of the input data, but are independent of the SPARQL endpoint. A "Book" view can be reused on all libraries and bookstore SPARQL endpoints that published data using the vocabulary that the view expects as input. Views are simple functions that do not require the developers to have a deep understanding of Semantic Web technologies: usual front-end knowledge is enough. Last but not least, SparqlExplorer is free/libre and open-source software. Do not hesistate to reuse and contribute!'
---
# SparqlExplorer, exploring Linked Open Data
[[Fabien Amarger]], [[Elodie Thieblin]], [[Chauvat Nicolas]]

Since developing and maintaining web applications is costly, a lot of the data published in [[SPARQL]] endpoints is difficult to explore by users that are not experts of LOD tools and languages. In order to make that data more accessible we developed [[SparqlExplorer]], a web application that can be plugged into any SPARQL endpoint to make its content browsable without writing a single query by applying views to render web pages. For example, to explore a dataset about books, SparqlExplorer would use a book-specific views that executes a SPARQL query to retrieve that data related to a book and generate a web page that displays the title, the [[ISBN]] and maybe a thumbnail of the cover.
Views are javascript functions that take data and output HTML. Views depend on the structure of the input data, but are independent of the SPARQL endpoint. A “Book” view can be reused on all libraries and bookstore SPARQL endpoints that published data using the vocabulary that the view expects as input. Views are simple functions that do not require the developers to have a deep understanding of Semantic Web technologies: usual front-end knowledge is enough.
Last but not least, SparqlExplorer is free/libre and open-source software. Do not hesistate to reuse and contribute!
