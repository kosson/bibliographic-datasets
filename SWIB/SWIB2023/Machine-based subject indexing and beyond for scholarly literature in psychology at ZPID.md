---
alias: SWIB
type: 'presentation'
event: Semantic Web in Libraries
year: 2023
partof: 'Collections'
tags:
  - '#PSYNDEX'
  - '#reference/database'
  - '#ZPID'
  - '#lexical/system'
  - '#AUTINDEX'
  - '#Annif'
  - '#workflow'
title: Machine-based subject indexing and beyond for scholarly literature in psychology at ZPID
alt: ''
resources:
  - 'https: //swib.org/swib23/slides/04_Tina%20Trillitzsch_Floria%20Gr%C3%A4ssle_Machine-based_subject_indexing_with_Annif_at_ZPID.pdf'
  - 'https: //youtu.be/cR5aBkyjFMo'
author:
  - Florian A. Grässle
  - Tina Trillitzsch
abstract: PSYNDEX is a reference database for psychological literature from German-speaking countries, growing at a rate of 1,000 new publications per month. The mostly scholarly papers in PSYNDEX are extensively catalogued by human indexers at ZPID (Leibniz Institute for Psychology) along several dimensions and vocabularies specific to psychological research. For the past 15 years, we used a lexical system (AUTINDEX) to generate keyword suggestions for our indexers, based on our vocabulary’s main concepts, synonyms and hidden indicators. This system has recently been replaced by the machine-learning based software Annif, and we plan to move to fully automated indexing for part of our records. In this presentation, we will discuss how we integrated Annif into our workflow and most importantly, how we try to assess and improve its suggestions.
---
# Machine-based subject indexing and beyond for scholarly literature in psychology at ZPID
[[Florian A. Grässle]], [[Tina Trillitzsch]]

PSYNDEX is a reference database for psychological literature from German-speaking countries, growing at a rate of 1,000 new publications per month. The mostly scholarly papers in PSYNDEX are extensively catalogued by human indexers at ZPID (Leibniz Institute for Psychology) along several dimensions and vocabularies specific to psychological research. For the past 15 years, we used a lexical system (AUTINDEX) to generate keyword suggestions for our indexers, based on our vocabulary’s main concepts, synonyms and hidden indicators. This system has recently been replaced by the machine-learning based software Annif, and we plan to move to fully automated indexing for part of our records. In this presentation, we will discuss how we integrated Annif into our workflow and most importantly, how we try to assess and improve its suggestions.
Indexers sporadically report specific concepts that Annif failed to suggest (false negatives), or that it wrongly suggested (false positives). We will discuss the “detective work” of classifying these concepts into problem categories and our strategies of dealing with each: e.g. exclusion lists for overly general concepts (“Diagnosis”), boosting new vocabulary concepts not appearing in the training set yet (“COVID-19”), or optimizing the vocabulary itself (like adding more synonyms so lexical parts of the backend can recognize infrequently used concepts). We will also report how we fared with automatically collecting exhaustive lists of such problem concepts by comparing Annif’s suggestions with the concepts actually accepted or added by human indexers. Finally, we will present our attempts at going beyond keyword indexing: automatically marking some suggestions as “weighted” (main vs secondary topics) and suggesting publication genre or type, study methodology, and study population.
