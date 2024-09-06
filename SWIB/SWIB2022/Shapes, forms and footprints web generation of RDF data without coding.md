---
alias: SWIB
type: lighning talk
event: SWIB 2022
year: "2022"
partof: "RDF Insights / Lightning Talks"
tags:
  - "#knowledge/graph"
  - "#ontology"
  - "#FormViewer"
  - "#Solid"
  - "#protocol"
title: "Shapes, forms and footprints: web generation of RDF data without coding"
alt: ''
resources:
  - "https: //swib.org/swib22/slides/20221201_swib_shapes_forms_footprints.pdf"
  - 'https: //youtu.be/Wj1_X9hrk4c'
author:
  - Patrick Hochstenbach
abstract: While browsing the Web a user is often confronted with a form requiring them to enter their personal data. We share book reviews on Goodreads; share our names, addresses and affiliations information with conference tools; submit our bibliography to institutional websites and centralized services such as ORCID. Filling out this information is a repetitive task for many users, using data that in principle should already be available in a knowledge graph somewhere. For the creation of (ad hoc) forms from scratch users do not have many options other than using platforms such as Google Forms which provide a limited set of input fields and a Google sheet as the end result, or asking their IT department to build a form which can require some time to implement and publish. During the COVID-19 pandemic many IT departments were asked to provide such ad hoc forms for all kinds of crowd sourcing where metadata was entered by library staff working from home. All these forms have hard-coded locations where the produced data needs to be stored, so a user has no choice in that matter. I will present an abstract way how RDF data can be read, updated, and stored in a decentralized way using RDF forms. The RDF data is defined by shapes, the forms are defined using a Form ontology, and the footprint (where to store the result) is also coded in RDF. All these inputs are web resources that declare to FormViewer apps how to read, update, and store data. An entire app can be written just by manipulating RDF resources, using the Solid protocol as persistence layer.
---
# Shapes, forms and footprints: web generation of RDF data without coding
[[Patrick Hochstenbach]]

While browsing the Web a user is often confronted with a form requiring them to enter their personal data. We share book reviews on Goodreads; share our names, addresses and affiliations information with conference tools; submit our bibliography to institutional websites and centralized services such as [[ORCID]]. Filling out this information is a repetitive task for many users, using data that in principle should already be available in a knowledge graph somewhere.
For the creation of (ad hoc) forms from scratch users do not have many options other than using platforms such as Google Forms which provide a limited set of input fields and a Google sheet as the end result, or asking their IT department to build a form which can require some time to implement and publish. During the COVID-19 pandemic many IT departments were asked to provide such ad hoc forms for all kinds of crowd sourcing where metadata was entered by library staff working from home. All these forms have hard-coded locations where the produced data needs to be stored, so a user has no choice in that matter.
I will present an abstract way how RDF data can be read, updated, and stored in a decentralized way using RDF forms. The RDF data is defined by shapes, the forms are defined using a Form [[ontology]], and the footprint (where to store the result) is also coded in RDF. All these inputs are web resources that declare to [[FormViewer]] apps how to read, update, and store data. An entire app can be written just by manipulating RDF resources, using the [[Solid]] protocol as persistence layer.
