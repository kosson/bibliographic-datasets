---
alias: SWIB
type: presentation
event: SWIB 2021
year: "2021"
partof: "Tools"
tags:
  - "#Bibframe"
  - "#JSON"
  - "#JSON-LD"
  - "#RERO+"
  - "#Swiss"
  - "#ILS"
title: Web editor for JSON/Bibframe data in libraries
alt: ''
resources:
  - "https: //swib.org/swib21/slides/03-05-prongue.pdf"
  - 'https: //youtu.be/uyG-V_ffJ8k'
author:
  - Nicolas Prongué
abstract: "This presentation shows a cataloguing form created to edit data stored in a Bibframe/JSON format. It points out the specificities, obstacles, advantages and difficulties of this implementation in comparison to a raw MARC editor. On the one hand, the interface must be really user-friendly, as it is targeted at public, school and special libraries. On the other hand, it must enable to receive granular bibliographic records from MARC and to edit JSON data that is hierarchically structured and deeply nested, composed of a multitude of fields with different conditionalities and validation rules. The system does not enable to create directly RDF data but it represents, in the specific library context, a relevant step towards the edition of linked and interoperable data. The next step regarding semantic web is to define a transformation and context for exposing this data in JSON-LD. This happens within the transition of RERO+, a Swiss competence and service centre for libraries, to an open source and in house library system called RERO ILS. About 60 libraries in Switzerland are using it since July 2021. In this context, it was decided to abandon MARC21 in favour of JSON, using the Bibframe model as far as possible and maintaining an interoperability for data import/export. RERO ILS is based on the Invenio 3 framework proposed by CERN, which heavily relies on JSON and JSON schema for resource management. The editor is also implemented within SONAR, another RERO+ software made to manage institutional repositories. RERO ILS source code: https://github.com/rero/rero-ils/"
---
# Web editor for JSON/Bibframe data in libraries
[[Nicolas Prongué]]

This presentation shows a cataloguing form created to edit data stored in a [[Bibframe]]/JSON format. It points out the specificities, obstacles, advantages and difficulties of this implementation in comparison to a raw [[MARC]] editor. On the one hand, the interface must be really user-friendly, as it is targeted at public, school and special libraries. On the other hand, it must enable to receive granular bibliographic records from MARC and to edit JSON data that is hierarchically structured and deeply nested, composed of a multitude of fields with different conditionalities and validation rules. The system does not enable to create directly RDF data but it represents, in the specific library context, a relevant step towards the edition of linked and interoperable data. The next step regarding semantic web is to define a transformation and context for exposing this data in JSON-LD. This happens within the transition of [[RERO+]], a [[Swiss]] competence and service centre for libraries, to an open source and in house library system called [[RERO ILS]]. About 60 libraries in Switzerland are using it since July 2021. In this context, it was decided to abandon MARC21 in favour of JSON, using the Bibframe model as far as possible and maintaining an interoperability for data import/export. RERO ILS is based on the Invenio 3 framework proposed by CERN, which heavily relies on JSON and JSON schema for resource management. The editor is also implemented within SONAR, another RERO+ software made to manage institutional repositories. RERO ILS source code: https://github.com/rero/rero-ils/.