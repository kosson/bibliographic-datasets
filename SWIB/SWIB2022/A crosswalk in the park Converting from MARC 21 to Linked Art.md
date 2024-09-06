---
alia: SWIB
type: presentation
event: SWIB 2022
year: "2022"
partof: "Linked Library Data I"
tags:
  - "#LUX"
  - "#CIDOC"
  - "#ontology"
  - "#Yale"
  - "#MARC/21"
  - "#discovery/environment"
  - "#JSON-LD"
title: A crosswalk in the park? Converting from MARC 21 to Linked Art
alt: ''
resources:
  - "https: //swib.org/swib22/slides/A%20Crosswalk%20in%20the%20Park%20Converting%20from%20MARC%2021%20to%20Linked%20Art-TimThompson_MartinLovell_v2.pdf"
  - "https: //www.youtube.com/watch?v=ZxkZnPerMgc"
author:
  - Martin Lovell
  - Timothy A. Thompson
abstract: Yale University is currently undertaking a multiyear effort to create a cross-collections discovery environment called LUX, or “light,” from the university’s Latin motto. LUX aggregates metadata from the catalogs of Yale’s four main collecting units, including the university library. The LUX platform has been designed using the Linked Art (LA) profile of the CIDOC CRM ontology as its common data model. Each collecting unit has developed a crosswalk from its local domain standard to the LA model. In the library, metadata librarians and software engineers have collaborated to develop and document a crosswalk from MARC 21 to LA JSON-LD - JavaScript Object Notation Linked Data. Implementing the crosswalk has meant designing a system that is more complex than a typical transformation. A single MARC record may be expanded into multiple top-level LA entities. In total, Yale’s 12.5 million catalog records translate into 47.5 million entities in LA. To implement the semantics of the LA model and manage data dependencies within and across MARC records, a new system was developed using Java and Spring Boot with Postgres. The system was designed to serve up LA entities, exposed through an activity stream, and to provide a framework for a modular set of transformation components. Generating linked data at scale was a new challenge for the library. The initial design used a database schema based on triples, with resolvable identifiers for all objects; this approach provided an intuitive way to create and query relationships without using a native triple store or graph database, given the learning curve that an unfamiliar system would have entailed. However, the triples-based approach proved too resource-intensive at scale, and the system was modified to store some data in JSON and resolve only top-level entities, while still storing a subset of the relationship data for querying.
---
# A crosswalk in the park? Converting from MARC 21 to Linked Art
[[Martin Lovell]], [[Timothy A. Thompson]]

Yale University is currently undertaking a multiyear effort to create a cross-collections discovery environment called [[LUX]], or “light,” from the university’s Latin motto. LUX aggregates metadata from the catalogs of Yale’s four main collecting units, including the university library. The LUX platform has been designed using the [[Linked Art]] (LA) profile of the [[CIDOC CRM]] [[ontology]] as its common data model. Each collecting unit has developed a crosswalk from its local domain standard to the LA model. In the library, metadata librarians and software engineers have collaborated to develop and document a crosswalk from [[MARC]] 21 to LA [[JSON-LD - JavaScript Object Notation Linked Data]]
Implementing the crosswalk has meant designing a system that is more complex than a typical transformation. A single MARC record may be expanded into multiple top-level LA entities. In total, Yale’s 12.5 million catalog records translate into 47.5 million entities in LA. To implement the semantics of the LA model and manage data dependencies within and across MARC records, a new system was developed using Java and Spring Boot with Postgres. The system was designed to serve up LA entities, exposed through an activity stream, and to provide a framework for a modular set of transformation components.
Generating linked data at scale was a new challenge for the library. The initial design used a database schema based on triples, with resolvable identifiers for all objects; this approach provided an intuitive way to create and query relationships without using a native triple store or graph database, given the learning curve that an unfamiliar system would have entailed. However, the triples-based approach proved too resource-intensive at scale, and the system was modified to store some data in JSON and resolve only top-level entities, while still storing a subset of the relationship data for querying.
