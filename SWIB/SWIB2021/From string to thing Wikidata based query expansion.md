---
alias: SWIB
type: presentation
event: SWIB 2021
year: "2021"
partof: "Discovery"
tags:
  - "#Wikidata"
  - "#Primo/VE"
  - "#SPARQL/queries"
title: "From string to thing: Wikidata based query expansion"
alt: ''
resources:
  - "https: //swib.org/swib21/slides/05-04-uttenweiler.pdf"
  - "https: //youtu.be/9CWx4IQyiA8"
author:
  - Bernd Uttenweiler
abstract: |
  'Our discovery system Primo VE (Ex Libris) returns a result list after entering a search string. Retrieval of resources by instances of the categories "Person" and "Place" is not possible. But these would have 2 advantages: We can better link (in both directions) to other sites that are built on persons or places. And: We can offer additional research support to our users, especially from the Digital Humanities field. We need to find a way from the entered search term (string) to the object (thing) "person" or "place". For this purpose, the user's "normal" search query is dynamically preprocessed by SPARQL queries against Wikidata in such a way that the user is provided with offers for matching places and people. When the user makes a selection from the list of persons or places, we have completed the step from string to thing. Besides, this allows names to be disambiguated and name variants that do not exist in the catalog to be taken into account. If the user makes a selection, then a person page or place page is rendered. On the person page are biographical information, links to other sites, researcher profiles, and archive holdings (from Wikidata, Entityfacts, beacon.findbuch, Metagrid). Among other things, teacher student relationships are also presented and the user can go to the teacher's or student's person page. Based on Wikidata graphs, the resources of the catalog are linked together in new ways. The presentation will provide insights into the objectives, decisions and implementation under Primo. The person and place pages are are implemented in our productive system. Selection options for the user within the search process are implemented in a test system and planned to go live soon. Link to Test system: Suggestions for persons'
---
# From string to thing: Wikidata based query expansion

[[Bernd Uttenweiler]]

Our discovery system [[Primo VE]] (Ex Libris) returns a result list after entering a search string. Retrieval of resources by instances of the categories “Person” and “Place” is not possible. But these would have 2 advantages: We can better link (in both directions) to other sites that are built on persons or places. And: We can offer additional research support to our users, especially from the Digital Humanities field. We need to find a way from the entered search term (string) to the object (thing) “person” or “place”. For this purpose, the user’s “normal” search query is dynamically preprocessed by [[SPARQL]] queries against [[Wikidata]] in such a way that the user is provided with offers for matching places and people. When the user makes a selection from the list of persons or places, we have completed the step from string to thing. Besides, this allows names to be disambiguated and name variants that do not exist in the catalog to be taken into account. If the user makes a selection, then a person page or place page is rendered. On the person page are biographical information, links to other sites, researcher profiles, and archive holdings (from Wikidata, Entityfacts, beacon.findbuch, Metagrid). Among other things, teacher student relationships are also presented and the user can go to the teacher’s or student’s person page. Based on Wikidata graphs, the resources of the catalog are linked together in new ways.
The presentation will provide insights into the objectives, decisions and implementation under [[Primo]]. The person and place pages are are implemented in our productive system. Selection options for the user within the search process are implemented in a test system and planned to go live soon. Link to Test system: Suggestions for persons.