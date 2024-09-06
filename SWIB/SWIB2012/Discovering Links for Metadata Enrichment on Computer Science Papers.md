---
alias: SWIB
type: presentation
event: SWIB 2012
year: '2012'
partof: ''
tags:
  - '#Silk'
  - '#n-triples'
  - '#SPARQL'
  - '#RDF'
  - '#dublin/core'
  - '#dcterms'
  - '#metadata/enrichment'
  - '#enrichment'
  - '#silk'
  - '#owl/sameAs'
title: Discovering Links for Metadata Enrichment on Computer Science Papers
alt: ''
resources:
  - https://swib.org/swib12/slides/Schaible_SWIB12_107.pdf
  - http://www.scivee.tv/node/55328
author:
  - Johann Schaible
  - Philipp Mayr
abstract: Libraries, which have collections of scientific papers, most of the times show only basic information comprising title, authors, publication date, and an abstract of a paper. The user can utilize this data to manually look up more information about the paper on the web. This is time-consuming though and simply not done by many users. In this paper we demonstrate a 3-step approach using semantic web technology, which consists of integrating Linked Data in order to enlarge metadata of a paper with links to external data sources. For this we use a link discovery tool, in our case Silk. Our initial record for each computer science paper consists of its title, its authors, and its publication date. This information is represented in simple RDF using the dcterms namespace, i.e. dcterms:title, dcterms:creator, and dcterms:date. As external data sources with the highest expectations of finding additional data we identified the DBLP computer science bibliography, the Association for Computing Machinery (ACM), and the Semantic Web Conference Corpus. In the first step we build a connection between our records and each of these data sources using Silk. By defining linkage rules e.g. link dcterms:title in data set 'a' and rdfs:label in data set 'b' and a matching scenario e.g. owl:sameAs, in the second step Silk looks up equal values in both data sources. If it finds an equal value, a link between data sets will be generated. All generated links are stored as n-triples. In the third step we manually add these links to our data set, enriching a paper’s metadata. We also illustrate our experiences with SILK regarding correctness and the handling of RDF dumps and SPARQL Endpoints.
---
# Discovering Links for Metadata Enrichment on Computer Science Papers

[[Johann Schaible]], [[Philipp Mayr]]

Libraries, which have collections of scientific papers, most of the times show only basic information comprising title, authors, publication date, and an abstract of a paper. The user can utilize this data to manually look up more information about the paper on the web. This is time-consuming though and simply not done by many users. In this paper we demonstrate a 3-step approach using semantic web technology, which consists of integrating Linked Data in order to enlarge metadata of a paper with links to external data sources. For this we use a link discovery tool, in our case [[Silk]]. Our initial record for each computer science paper consists of its title, its authors, and its publication date. This information is represented in simple RDF using the [[dcterms]] namespace, i.e. dcterms:title, dcterms:creator, and dcterms:date. As external data sources with the highest expectations of finding additional data we identified the [[DBLP]] computer science bibliography, the Association for Computing Machinery ([[ACM]]), and the [[Semantic Web Conference]] Corpus. In the first step we build a connection between our records and each of these data sources using Silk. By defining linkage rules e.g. link dcterms:title in data set ‘a’ and rdfs:label in data set ‘b’ and a matching scenario e.g. owl:sameAs, in the second step Silk looks up equal values in both data sources. If it finds an equal value, a link between data sets will be generated. All generated links are stored as [[n-triples]]. In the third step we manually add these links to our data set, enriching a paper’s metadata. We also illustrate our experiences with SILK regarding correctness and the handling of RDF dumps and [[SPARQL]] Endpoints.
