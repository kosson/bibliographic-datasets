---
alias: SWIB
type: presentation
event: SWIB 2019
year: "2019"
partof: "A long way to go"
tags:
  - "#MARC"
  - "#user/tasks"
  - "#metadata"
  - "#FRBR"
title: Empirical evaluation of library catalogues
alt: ''
resources:
  - "http: //bit.ly/qa-swib2019"
  - 'https: //youtu.be/qfPAc5QhSFM'
author:
  - Péter Király
abstract: The library community is in the transition period from Machine Readable Cataloguing (MARC) to some linked data based metadata schema. MARC is complex both as data structure and as semantic structure. This complexity leads to a wide range of errors. When we transform records from MARC to semantic schemas, we should not suppose that we have structurally and semantically perfect records. The aim of this presentation is to call attention to the typical issues revealed by an investigation of 16 library catalogues. The most frequent issue types are usage of undocumented schema elements, then improper values in places where a value should be taken from a dictionary, or should match to other strict requirements. MARC has a number of features which makes validation a challenge such as intensive use of information compressing and encoding techniques, versions without versioning, dependency on internal and external data dictionaries, it is huge (the “core” MARC21 has about 3000 semantic data elements, while other versions defined several hundreds more), and the standard itself is not a machine-readable rule set. Some of these errors might block the transformation of the records, some others might survive in the new structure as well if we do not fix them. The research aims to detect different issues of the metadata records. The foremost of them are those which do not fit the rules defined by the standard. Organized by structure the tool detects issues on record level, in control fields, in data fields, in indicators and in subfields. It also calculates completeness, Thompson-Traill completeness, runs a functional analysis based on the FRBR defined “user tasks” and provides a web based user interface. In the research process a tool has been built which contains an (exportable) object model of the standard.
---
# Empirical evaluation of library catalogues
[[Péter Király]]

The library community is in the transition period from Machine Readable Cataloguing ([[MARC]]) to some linked data based metadata schema. MARC is complex both as data structure and as semantic structure. This complexity leads to a wide range of errors. When we transform records from MARC to semantic schemas, we should not suppose that we have structurally and semantically perfect records. The aim of this presentation is to call attention to the typical issues revealed by an investigation of 16 library catalogues. The most frequent issue types are usage of undocumented schema elements, then improper values in places where a value should be taken from a dictionary, or should match to other strict requirements.
MARC has a number of features which makes validation a challenge such as intensive use of information compressing and encoding techniques, versions without versioning, dependency on internal and external data dictionaries, it is huge (the “core” MARC21 has about 3000 semantic data elements, while other versions defined several hundreds more), and the standard itself is not a machine-readable rule set. Some of these errors might block the transformation of the records, some others might survive in the new structure as well if we do not fix them. The research aims to detect different issues of the metadata records. The foremost of them are those which do not fit the rules defined by the standard. Organized by structure the tool detects issues on record level, in control fields, in data fields, in indicators and in subfields. It also calculates completeness, Thompson-Traill completeness, runs a functional analysis based on the FRBR defined “user tasks” and provides a web based user interface. In the research process a tool has been built which contains an (exportable) object model of the standard.
