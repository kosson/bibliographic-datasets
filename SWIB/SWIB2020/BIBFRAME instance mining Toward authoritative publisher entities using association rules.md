---
alias: SWIB
type: presentation
event: SWIB 2020
year: "2020"
partof: "Authorities"
tags:
  - "#Share-VDE"
  - "#project"
  - "#enrichment"
  - "#BIBFRAME"
  - "#data/mining"
  - "#machine/learning"
  - "#ISBN"
  - "#MARC"
title: "BIBFRAME instance mining: Toward authoritative publisher entities using association rules"
alt: ''
resources:
  - "https: //swib.org/swib20/slides/03-04-hahn.pdf"
  - 'https: //youtu.be/ZzxSnBa1tOU'
author:
  - Jim Hahn
abstract: The catalyst for this talk stems from work within the Share-VDE initiative, a shared discovery environment based on linked data. The project encompasses enrichment with linked open data and subsequent conversion from MARC to BIBFRAME/RDF and creation of a cluster knowledge base made up of over 400 million triples. The resulting BIBFRAME network is comprised of the BIBFRAME entities Work and Instance, among other Share-VDE specific entities. With the transition of a shared catalog to BIBFRAME linked data, there is now a pressing need for identifying the canonical Instance for clustering in BIBFRAME. A fundamental component of Instance identification is by way of authoritative publisher entities. Previous work in this area by OCLC research (Connaway & Dickey, 2011) proposed a data mining approach for developing an experimental Publisher Name Authority File (PNAF). The OCLC research was able to create profiles for "high-incidence" publishers after data mining and clustering of publishers. As a component of PNAF, Connaway & Dickney were able to provide detailed subject analysis of publishers. This presentation will detail a case study of machine learning methods over a corpus of subjects, main entries, and added entries, as antecedents into association rules to derive consequent publisher entities. The departure point for the present research into identification of authoritative publisher entities is to focus on clustering, reconciliation and re-use of ISBN and subfield b of MARC 260 along with the subjects (650 - Subject Added Entry), main entries (1XX - Main Entries) and added entries (710 - Added Entry-Corporate Name) as signals to inform a training corpus into association rule mining, among other machine learning algorithms, libraries, and methods.
---
# BIBFRAME instance mining: Toward authoritative publisher entities using association rules

[[Jim Hahn]]

The catalyst for this talk stems from work within the [[Share-VDE]] initiative, a shared discovery environment based on linked data. The project encompasses enrichment with linked open data and subsequent conversion from MARC to BIBFRAME/RDF and creation of a cluster knowledge base made up of over 400 million triples. The resulting BIBFRAME network is comprised of the [[BIBFRAME]] entities Work and Instance, among other Share-VDE specific entities.
With the transition of a shared catalog to BIBFRAME linked data, there is now a pressing need for identifying the canonical Instance for clustering in BIBFRAME. A fundamental component of Instance identification is by way of authoritative publisher entities. Previous work in this area by OCLC research (Connaway &amp; Dickey, 2011) proposed a data mining approach for developing an experimental Publisher Name Authority File ([[PNAF]]). The OCLC research was able to create profiles for “high-incidence” publishers after data mining and clustering of publishers. As a component of PNAF, Connaway &amp; Dickney were able to provide detailed subject analysis of publishers. This presentation will detail a case study of [[GLOSSARY/machine learning]] methods over a corpus of subjects, main entries, and added entries, as antecedents into association rules to derive consequent publisher entities. The departure point for the present research into identification of authoritative publisher entities is to focus on clustering, reconciliation and re-use of ISBN and subfield b of MARC 260 along with the subjects (650 - Subject Added Entry), main entries (1XX - Main Entries) and added entries (710 - Added Entry-Corporate Name) as signals to inform a training corpus into association rule mining, among other machine learning algorithms, libraries, and methods.
