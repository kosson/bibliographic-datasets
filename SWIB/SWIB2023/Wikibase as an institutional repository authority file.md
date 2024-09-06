---
alias: SWIB
type: 'presentation'
event: Semantic Web in Libraries
year: 2023
partof: 'Authorities'
tags:
  - '#Berkeley/Law/Library'
  - '#institutional/repository'
  - '#TIND'
  - '#authority/records'
  - '#Wikidata/QID'
  - '#API'
  - '#ORCiD'
title: Wikibase as an institutional repository authority file
alt: ''
resources:
  - 'https: //swib.org/swib23/slides/05_Joe%20Cera_Michael%20Lindsey_Authorities%20presentation.pdf'
  - 'https: //youtu.be/aKC0SiGp0H4'
author:
  - Joe Cera
  - Michael Lindsey
abstract: |-
  The Berkeley Law Library manages the institutional repository (IR) for Berkeley Law. The IR is part of the institutional TIND integrated library system (ILS). Since these systems are linked through many shared functionalities, we explored various options for creating authority records for the IR that wouldn’t interfere with the ILS authority records file. Prior to this effort, there were no authority records for the IR and all data was added manually which created a great potential for data to be out of sync.
  For the past 5 years, we have been using Wikidata QIDs as Berkeley Law faculty identifiers in the IR. In order to maintain consistency, we used the Wikidata API to create an external HTML page used to gather a handful of properties for each QID in the IR which would make manual entry easier and more consistent. In the past 6 months, the IR platform had an authority file update which motivated us to move away from a spreadsheet approach to managing the structure of these records to a more linked data friendly and dynamic method. We created a Wikibase using the wikibase.cloud platform to host this data and explore the potential of using our own Wikibase for internal applications. This instance helps us track data that is more local to our needs while also maintaining connections to other data sources. Entity modification timestamps and revision IDs are used to determine whether or not to initiate an update to our wikibase or to wikidata itself. Updates are limited to a controlled list of properties, such as Library of Congress identifiers, ORCiD, CV, etc. Directionality of particular properties is governed at the application level by the narrative logic of the script.
---
# Wikibase as an institutional repository authority file
[[Joe Cera]], [[Michael Lindsey]]

The Berkeley Law Library manages the institutional repository (IR) for Berkeley Law. The IR is part of the institutional TIND integrated library system (ILS). Since these systems are linked through many shared functionalities, we explored various options for creating authority records for the IR that wouldn’t interfere with the ILS authority records file. Prior to this effort, there were no authority records for the IR and all data was added manually which created a great potential for data to be out of sync.
For the past 5 years, we have been using Wikidata QIDs as Berkeley Law faculty identifiers in the IR. In order to maintain consistency, we used the Wikidata API to create an external HTML page used to gather a handful of properties for each QID in the IR which would make manual entry easier and more consistent. In the past 6 months, the IR platform had an authority file update which motivated us to move away from a spreadsheet approach to managing the structure of these records to a more linked data friendly and dynamic method. We created a Wikibase using the wikibase.cloud platform to host this data and explore the potential of using our own Wikibase for internal applications. This instance helps us track data that is more local to our needs while also maintaining connections to other data sources. Entity modification timestamps and revision IDs are used to determine whether or not to initiate an update to our wikibase or to wikidata itself. Updates are limited to a controlled list of properties, such as Library of Congress identifiers, ORCiD, CV, etc. Directionality of particular properties is governed at the application level by the narrative logic of the script.