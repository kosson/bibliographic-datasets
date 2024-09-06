---
alias: SWIB
type: 'presentation'
event: Semantic Web in Libraries
year: 2023
partof: 'Collections'
tags:
  - '#portal'
  - '#Vitro'
  - '#drawings'
  - '#art-historical/collection'
  - '#Albrecht/Haupt'
title: Implementation of the Albrecht Haupt collection portal based on the general-purpose semantic web application Vitro
alt: ''
resources:
  - 'https: //swib.org/swib23/slides/05_Walther_Litvinov_SWIB%202023%20GESAH.pdf'
  - 'https: //youtu.be/sMPanaN8Xs0'
author:
  - Georgy Litvinov
  - Birte Rubach
  - Tatiana Walther
abstract: "The Albrecht Haupt Collection is a collection of European drawings and prints, which became publicly available this year on\_[sah.tib.eu](https://sah.tib.eu/). In this presentation, we describe adoptions of a standard Vitro implemented for indexing environment of an art-historical collection according to the special needs of art-historians on the one hand and linked data principles on the other hand and making it available for further use by experts, broad audience and art-historical Web portals. We also address the technical challenges encountered in the process as well as further developments we are working on."
---
# Implementation of the Albrecht Haupt collection portal based on the general-purpose semantic web application Vitro
[[Georgy Litvinov]], [[Birte Rubach]], [[Tatiana Walther]]

The Albrecht Haupt Collection is a collection of European drawings and prints, which became publicly available this year on <a href="https://sah.tib.eu/">sah.tib.eu</a>. In this presentation, we describe adoptions of a standard Vitro implemented for indexing environment of an art-historical collection according to the special needs of art-historians on the one hand and linked data principles on the other hand and making it available for further use by experts, broad audience and art-historical Web portals. We also address the technical challenges encountered in the process as well as further developments we are working on.
To describe the items in alignment with standards of cultural data description and export such as the CIDOC CRM and LIDO, the <a href="https://github.com/tibonto/gesah">GESAH Graphic Arts Ontology</a> was created as an event-centered ontology. Thus, cultural objects are described by a number of activities like e. g. creation or production, agents having various roles in these activities and other attributes e.g. used technique or material. The ontology and collection metadata has been enriched with PIDs from Art &amp; Architecture Thesaurus, ICONCLASS, Getty Thesaurus of Geographic Names, GND and Wikidata. Apart from the specific ontology, new entry forms and display modifications were implemented in an iterative and user-centered approach based on feedback from art historians for recording and representing metadata related to the collection items. We integrated Cantaloupe IIIF to provide instant access to high definition images. Furthermore we developed a highly customizable search that allows users to limit the results area using various filters. A challenge we are currently facing is exporting collection object descriptions to other formats such as LIDO. We will introduce the Dynamic API for the VIVO project with which we aim to solve the aforementioned challenges.
