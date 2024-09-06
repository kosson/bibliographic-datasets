---
alias: SWIB
type: presentation
event: SWIB 2021
year: "2021"
partof: "Controlled vocabularies"
tags:
  - "#OpenRefine"
  - "#clustering"
  - "#reconciliation"
  - "#ElexiFinder"
  - "#LexBib"
title: String matching algorithms in OpenRefine clustering and reconciliation functions - a case study of person name matching
alt: ''
resources:
  - "https: //swib.org/swib21/slides/03-01-klaes.pdf"
  - 'https: //youtu.be/j5ZucdP1ykw'
author:
  - Christiane Klaes
abstract: Person entities are important linking nodes both within and between Linked Open Data resources across different domains and use cases. Therefore, efficient identity management is a crucial part of resource development and maintenance. This case study is concerned with the task of semi-automatic population of a newly developed domain knowledge graph, LexBib Wikibase with high-quality person data. We aim to transform person name literals taken from publication metadata into Semantic Web entities, to enable improved retrieval and entity enrichment for the domain-specific discovery portal ElexiFinder. In a prototype workflow, the open source tool OpenRefine is used as a one-tool solution to perform deduplication, disambiguation and reconciliation of person names with reference datasets, using a sample of 3.104 name literals taken from LexBib bibliography. We closely examine OpenRefine’s clustering functions with its underlying string matching algorithms, focusing on their ability to account for different error types that frequently occur in person name matching, such as spelling errors, phonetic variations, initials, or double names. Following the same approach, string matching processes implemented in two widely used reconciliation services for Wikidata and VIAF are examined. OpenRefine offers various features. We also analyse the usefulness of OpenRefine features to support further processing of algorithmic output. The results of this case study may contribute to a better understanding and subsequent further development of interlinking features in OpenRefine and adjoining reconciliation services. By offering empiric data on OpenRefine’s underlying string matching algorithms, the study’s results supplement existing guides and tutorials on clustering and reconciliation, especially for person name matching projects.
---
# String matching algorithms in OpenRefine clustering and reconciliation functions - a case study of person name matching
[[Christiane Klaes]]

Person entities are important linking nodes both within and between Linked Open Data resources across different domains and use cases. Therefore, efficient identity management is a crucial part of resource development and maintenance. This case study is concerned with the task of semi-automatic population of a newly developed domain knowledge graph, LexBib Wikibase with high-quality person data. We aim to transform person name literals taken from publication metadata into Semantic Web entities, to enable improved retrieval and entity enrichment for the domain-specific discovery portal [[ElexiFinder]].
In a prototype workflow, the open source tool OpenRefine is used as a one-tool solution to perform deduplication, disambiguation and reconciliation of person names with reference datasets, using a sample of 3.104 name literals taken from LexBib bibliography. We closely examine OpenRefine’s clustering functions with its underlying string matching algorithms, focusing on their ability to account for different error types that frequently occur in person name matching, such as spelling errors, phonetic variations, initials, or double names. Following the same approach, string matching processes implemented in two widely used reconciliation services for Wikidata and VIAF are examined. OpenRefine offers various features. We also analyse the usefulness of OpenRefine features to support further processing of algorithmic output.
The results of this case study may contribute to a better understanding and subsequent further development of interlinking features in OpenRefine and adjoining reconciliation services. By offering empiric data on OpenRefine’s underlying string matching algorithms, the study’s results supplement existing guides and tutorials on clustering and reconciliation, especially for person name matching projects.
