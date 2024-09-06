---
alias: SWIB
type: presentation
event: SWIB 2018
year: '2018'
partof: 'Automating LOD'
tags:
  - '#BnF'
  - '#RDF'
  - '#enrichment'
title: 'data.bnf.fr as a sandbox for FRBRization: automated work creation in data.bnf.fr'
alt: ''
resources:
  - 'https: //swib.org/swib18/slides/2_lapotre_data-bnf-fr.pdf'
  - 'https: //youtu.be/-cabjegojNw'
author:
  - Sébastien Peyrard
  - Etienne Cavalié
  - Aude Le Moullec-Rieu
  - Raphaëlle Lapôtre
abstract: 'The French national library uses the data.bnf.fr online platform as an interface to disseminate its metadata on the semantic web. Source metadata includes notably, but is not limited to, MARC records to be converted and published as RDF triples, with authority records used as the basis for data.bnf.fr landing pages; the RDF graph is also enriched with alignments with external resources or FRBR relations between internal entities. 2018 is a game changer as a number of works displayed in data.bnf.fr will not be grounded on existing authority records, but will be automatically computed from clusters of bibliographic records. The first corpus for this will be the French textual works from the XXth and XXIst centuries, for which several hundred thousands works will be created. These works will be available as web pages available on the data.bnf.fr public interface, and as RDF data retrievable through the data.bnf.fr SPARQL Endpoint. In the long run, such works will be uploaded as MARC authority records in the main catalog and will comply with the traditional workflow where data.bnf.fr feeds on the BnF catalogue to generate its entities with persistent identifiers and records. In the meantime, the BnF must find answers to a number of questions: - Which data can reliably be used to group together bibliographic records as manifestations of a same work? - Which data can be used from those bibliographic records to compute work-level metadata? - What identifier can we use to identify such works that will not be persistent until they are uploaded in the BnF catalogue? - How can we promote this new metadata and inform its reuse by communicating about their specific nature and limits? The contribution will present methods and tools, steps and questions the data.bnf.fr team encountered in this process.'
---
# data.bnf.fr as a sandbox for FRBRization: automated work creation in data.bnf.fr
[[Sébastien Peyrard]], [[Etienne Cavalié]], [[Aude Le Moullec-Rieu]], [[Raphaëlle Lapôtre]]

The French national library uses the [[data.bnf.fr]] online platform as an interface to disseminate its metadata on the semantic web. Source metadata includes notably, but is not limited to, [[MARC]] records to be converted and published as [[RDF]] triples, with authority records used as the basis for data.bnf.fr landing pages; the RDF graph is also enriched with alignments with external resources or [[FRBR]] relations between internal entities. 2018 is a game changer as a number of works displayed in data.bnf.fr will not be grounded on existing authority records, but will be automatically computed from clusters of bibliographic records. The first corpus for this will be the French textual works from the XXth and XXIst centuries, for which several hundred thousands works will be created. These works will be available as web pages available on the data.bnf.fr public interface, and as RDF data retrievable through the data.bnf.fr [[SPARQL]] Endpoint. In the long run, such works will be uploaded as MARC authority records in the main catalog and will comply with the traditional workflow where data.bnf.fr feeds on the [[BnF]] catalogue to generate its entities with persistent identifiers and records. In the meantime, the BnF must find answers to a number of questions: - Which data can reliably be used to group together bibliographic records as manifestations of a same work? - Which data can be used from those bibliographic records to compute work-level metadata? - What identifier can we use to identify such works that will not be persistent until they are uploaded in the BnF catalogue? - How can we promote this new metadata and inform its reuse by communicating about their specific nature and limits? The contribution will present methods and tools, steps and questions the data.bnf.fr team encountered in this process.
