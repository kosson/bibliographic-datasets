---
alias: SWIB
type: presentation
event: SWIB 2016
year: '2016'
partof: 'Vizualization & Images'
tags:
  - '#iiif'
  - '#iiif/api'
  - '#linke/open/data/model'
  - '#Fedora'
  - '#JSON-LD'
  - '#RDF/graph'
title: Implementing the IIIF Presentation 2.0 API as a Linked Open Data Model in the Fedora Repository
alt: ''
resources:
  - 'https: //youtu.be/1KatIxhQx0E'
author:
  - Christopher Hanna Johnson
abstract: '"The IIIF Presentation API specifies a web service that returns JSON-LD structured documents that together describe the structure and layout of a digitized object or other collection of images and related content." IIIF website The dynamic serialization of IIIF JSON-LD structured manifests via SPARQL CONSTRUCT is an interesting possibility that has great potential for cross-domain discovery and rendering of digitized objects with variable criteria. I have explored this possibility by implementing a data model in the Fedora Commons Repository that matches the specifications of the IIIF Presentation API. Fedora has the facility to index objects via Apache Camel directly to a triplestore. With SPARQL CONSTRUCT, the triplestore can serialize normalized JSON-LD - JavaScript Object Notation Linked Data as a graph. The use of "ordered lists" (aka collections) is a fundamental component of JSON-LD and necessary feature of the IIIF manifest sequence which is represented in a canonical RDF graph as a cascade of blank nodes. In order to dynamically create the sequence with SPARQL requires that the data is modelled identically to the IIIF specification. This gist is a representation of a compacted and framed JSON-LD graph that was serialized from a SPARQL query of Fedora metadata. The ability to assemble parts of distinct, disparate and disassociated digital objects on demand in one cohesive presentation becomes a real possibility. For example, the "range" object is equivalent to a part of a sequence, like a chapter in a book. With SPARQL, it is possible to target ranges from different "editions" based on a metadata specification (i.e. a person, place, or date) and unify them in a manifest object which is then rendered by a client viewer like OpenSeadragon.'
---
# Implementing the IIIF Presentation 2.0 API as a Linked Open Data Model in the Fedora Repository
[[Christopher Hanna Johnson]]

“The IIIF Presentation API specifies a web service that returns [[JSON-LD]] structured documents that together describe the structure and layout of a digitized object or other collection of images and related content.” IIIF website The dynamic serialization of [[IIIF]] JSON-LD structured manifests via SPARQL CONSTRUCT is an interesting possibility that has great potential for cross-domain discovery and rendering of digitized objects with variable criteria. I have explored this possibility by implementing a data model in the Fedora Commons Repository that matches the specifications of the IIIF Presentation API. Fedora has the facility to index objects via Apache Camel directly to a triplestore. With [[SPARQL CONSTRUCT]], the triplestore can serialize normalized [[JSON-LD - JavaScript Object Notation Linked Data]] as a graph. The use of “ordered lists” (aka collections) is a fundamental component of JSON-LD and necessary feature of the IIIF manifest sequence which is represented in a canonical RDF graph as a cascade of blank nodes. In order to dynamically create the sequence with SPARQL requires that the data is modelled identically to the IIIF specification. This gist is a representation of a compacted and framed JSON-LD graph that was serialized from a SPARQL query of Fedora metadata. The ability to assemble parts of distinct, disparate and disassociated digital objects on demand in one cohesive presentation becomes a real possibility. For example, the “range” object is equivalent to a part of a sequence, like a chapter in a book. With SPARQL, it is possible to target ranges from different “editions” based on a metadata specification (i.e. a person, place, or date) and unify them in a manifest object which is then rendered by a client viewer like [[OpenSeadragon]].
