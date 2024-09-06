---
alias: SWIB
type: presentation
event: SWIB 2016
year: '2016'
partof: 'Vizualization & Images'
tags:
  - '#RDF'
  - '#visualization'
  - '#rdfpuml'
  - '#PlantUML'
  - '#GraphViz'
  - '#puml'
  - '#rdf2rdb'
title: 'RDF by Example: rdfpuml for True RDF Diagrams, rdf2rml for R2RML Generation'
alt: ''
resources:
  - 'http: //vladimiralexiev.github.io/pres/20161128-rdfpuml-rdf2rml/'
  - 'https: //youtu.be/4WoYlaGF6DE'
author:
  - Vladimir Alexiev
abstract: 'RDF is a graph data model, so the best way to understand RDF data schemas (ontologies, application profiles, RDF shapes) is with a diagram. Many RDF visualization tools exist, but they either focus on large graphs (where the details are not easily visible), or the visualization results are not satisfactory, or manual tweaking of the diagrams is required. We describe a tool *rdfpuml* that makes true diagrams directly from Turtle examples using PlantUML and GraphViz. Diagram readability is of prime concern, and rdfpuml introduces various diagram control mechanisms using triples in the puml: namespace. Special attention is paid to inlining and visualizing various Reification mechanisms (described with PRV). We give examples from Getty CONA, Getty Museum, AAC (mappings of museum data to CIDOC CRM), Multisensor (NIF and FrameNet), EHRI (Holocaust Research into Jewish social networks), Duraspace (Portland Common Data Model for holding metadata in institutional repositories), Video annotation. If the example instances include SQL queries and embedded field names, they can describe a mapping precisely. Another tool *rdf2rdb* generates R2RML transformations from such examples, saving about 15x in complexity.'
---
# RDF by Example: rdfpuml for True RDF Diagrams, rdf2rml for R2RML Generation
[[Vladimir Alexiev]]

RDF is a graph data model, so the best way to understand RDF data schemas (ontologies, application profiles, RDF shapes) is with a diagram. Many RDF visualization tools exist, but they either focus on large graphs (where the details are not easily visible), or the visualization results are not satisfactory, or manual tweaking of the diagrams is required. We describe a tool <em>rdfpuml</em> that makes true diagrams directly from Turtle examples using [[PlantUML]] and GraphViz. Diagram readability is of prime concern, and rdfpuml introduces various diagram control mechanisms using triples in the [[puml]]: namespace. Special attention is paid to inlining and visualizing various Reification mechanisms (described with PRV). We give examples from Getty CONA, Getty Museum, AAC (mappings of museum data to CIDOC CRM), Multisensor (NIF and FrameNet), EHRI (Holocaust Research into Jewish social networks), Duraspace (Portland Common Data Model for holding metadata in institutional repositories), Video annotation. If the example instances include SQL queries and embedded field names, they can describe a mapping precisely. Another tool <em>rdf2rdb</em> generates R2RML transformations from such examples, saving about 15x in complexity.
