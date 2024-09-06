---
alias: SWIB
type: presentation
event: SWIB 2021
year: "2021"
partof: "Controlled vocabularies"
tags:
  - "#BIBFRAME"
  - "#LCSH"
  - "#Annif"
  - "#API"
title: Semi-automated methods for BIBFRAME work entity description
alt: ''
resources:
  - "https: //swib.org/swib21/slides/03-03-hahn.pdf"
  - 'https: //youtu.be/RheGZhu13bs'
author:
  - Jim Hahn
abstract: Describing library resources with the BIBFRAME vocabulary and its core entities of Work, Instance, and Item is a resource intensive process. Cataloging in linked data RDF editors with BIBFRAME involves careful selection of, and referencing to, external authority entities. Creating external authoritative links is essential to produce an accurate context while describing the BIBFRAME Work entity in an RDF editor. This presentation will report an investigation of machine learning methods for the semi-automated creation of a BIBFRAME Work entity description within the RDF linked data editor Sinopia. The automated subject indexing software Annif was configured with the Library of Congress Subject Headings (LCSH) vocabulary from the Linked Data Service. A dataset comprising 9.3 million titles and LCSH linked data references from the IvyPlus POD project was used as the training corpus. POD is a data aggregation project involving member institutions of the IvyPlus Library Confederation and contains over seventy million MARC21 records, nearly 40 million of which are unique to the corpus. The machine learning outputs, accessed by Annif web API, enable a feature for dynamically auto suggesting subject attributes based on a cataloger supplied title. This method of research and development is foregrounded with considerations for ethical use of semi-automated subject description. Semi-automation as a potential integration target is in contrast to completely automated cataloging and is a very specific use of machine learning. In this work automation was used as a way to support, not replace, professional expertise.
---
# Semi-automated methods for BIBFRAME work entity description

[[Jim Hahn]]

Describing library resources with the [[BIBFRAME]] vocabulary and its core entities of Work, Instance, and Item is a resource intensive process. Cataloging in linked data [[RDF]] editors with BIBFRAME involves careful selection of, and referencing to, external authority entities. Creating external authoritative links is essential to produce an accurate context while describing the BIBFRAME Work entity in an RDF editor.
This presentation will report an investigation of machine learning methods for the semi-automated creation of a BIBFRAME Work entity description within the RDF linked data editor Sinopia. The automated subject indexing software Annif was configured with the Library of Congress Subject Headings (LCSH) vocabulary from the Linked Data Service. A dataset comprising 9.3 million titles and LCSH linked data references from the IvyPlus POD project was used as the training corpus. POD is a data aggregation project involving member institutions of the IvyPlus Library Confederation and contains over seventy million [[MARC21]] records, nearly 40 million of which are unique to the corpus.
The machine learning outputs, accessed by [[Annif]] web [[API]], enable a feature for dynamically auto suggesting subject attributes based on a cataloger supplied title. This method of research and development is foregrounded with considerations for ethical use of semi-automated subject description. Semi-automation as a potential integration target is in contrast to completely automated cataloging and is a very specific use of machine learning. In this work automation was used as a way to support, not replace, professional expertise.