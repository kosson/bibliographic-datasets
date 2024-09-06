---
alias: SWIB
type: presentation
event: SWIB 2020
year: "2020"
partof: "Automated subject indexing"
tags:
  - "#ZBW"
  - "#machine/learning"
  - "#automated/subject/indexing"
  - "#indexing"
  - "#metadata"
  - "#API"
  - "#statistics"
  - "#neural/networks"
title: "AutoSE@ZBW: Building a productive system for automated subject indexing at a scientific library"
alt: ''
resources:
  - "https: //swib.org/swib20/slides/01-03-kasprzik.pdf"
  - 'https: //youtu.be/5iBuY01tJPc'
author:
  - Anna Kasprzik
  - Moritz Fürneisen
  - Christopher Bartz
abstract: "At ZBW we have been developing prototype machine learning solutions for an automated subject indexing in the context of applied research for several years now. However, and as of 2019 these solutions were yet to be integrated into the metadata management system and into the subject indexing workflows at ZBW. It turns out that building a corresponding software architecture is a challenge on another level which requires additional resources on top of those for academic research as well as additional expertise. In order to create a productive system that makes these machine learning solutions usable in practice and that allows a continuous development we need to look at aspects such as user and data interfaces, suitable development and test environments, system stability, modularity and continuous integration. After a strategic reorientation and preparation phase in 2019, in 2020 we have created a first proof-of-concept version of a productive system that suggests subject terms for resources from our holdings and which makes these suggestions available via an API for example to the DA-3: a tool for assisted subject indexing based on suggestions from external sources that is currently evaluated in our library network. In parallel, we have been experimenting with more advanced statistical algorithms as well as with neural networks. Our software architecture is supposed to allow the integration of new methods as smoothly as possible without interruptions to the service. This presentation sums up our first steps towards a productive system, first lessons learned, and projects some milestones for the way ahead."
---
# AutoSE@ZBW: Building a productive system for automated subject indexing at a scientific library
[[Anna Kasprzik]], [[Moritz Fürneisen]], [[Christopher Bartz]]

At [[ZBW]] we have been developing prototype machine learning solutions for an automated subject indexing in the context of applied research for several years now. However, and as of 2019 these solutions were yet to be integrated into the metadata management system and into the subject indexing workflows at ZBW. It turns out that building a corresponding software architecture is a challenge on another level which requires additional resources on top of those for academic research as well as additional expertise. In order to create a productive system that makes these machine learning solutions usable in practice and that allows a continuous development we need to look at aspects such as user and data interfaces, suitable development and test environments, system stability, modularity and continuous integration.
After a strategic reorientation and preparation phase in 2019, in 2020 we have created a first proof-of-concept version of a productive system that suggests subject terms for resources from our holdings and which makes these suggestions available via an [[API]] for example to the DA-3: a tool for assisted subject indexing based on suggestions from external sources that is currently evaluated in our library network.
In parallel, we have been experimenting with more advanced statistical algorithms as well as with neural networks. Our software architecture is supposed to allow the integration of new methods as smoothly as possible without interruptions to the service.
This presentation sums up our first steps towards a productive system, first lessons learned, and projects some milestones for the way ahead.
