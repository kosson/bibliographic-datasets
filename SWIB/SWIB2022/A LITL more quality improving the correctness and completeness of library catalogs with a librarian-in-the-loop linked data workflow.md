---
alias: SWIB
type: presentation
event: SWIB 2022
year: "2022"
partof: "Linked Library Data I"
tags:
  - "#KBR"
  - "#BELTRANS"
  - "#project"
  - "#SPARQL"
  - "#linked/data"
  - "#Python"
title: "A LITL more quality: improving the correctness and completeness of library catalogs with a librarian-in-the-loop linked data workflow"
alt: ''
resources:
  - "https: //swib.org/swib22/slides/2022-11-28_SWIB_Sven-Lieber.pdf"
  - "https: //youtu.be/r29W73vle2I"
author:
  - Sven Lieber
  - Ann Van Camp
  - Hannes Lowagie
abstract: Traditionally, a library maintains both bibliographic data about publications and authority data about publication contributors such as authors or publishers. At the Royal Library of Belgium (KBR), we currently maintain more than 900,000 authority records about persons and metadata records of over 3.5 million publications. As an authoritative data source we are expected to have correct and complete data. In contrast to syntactical data quality issues – which can be detected automatically – issues regarding the correctness of data or completeness of the catalogue often require semantic checks, e.g., if the correct ISBN is used and if the nationality of the contributor is correct. However, the amount of Belgian cultural heritage data makes manual quality checks very time-consuming. Within the BELTRANS project which studies Intra-Belgian book translation flows of publications based on metadata (who?, when?, where?), we developed an approach to support librarians in the detection and correction of semantic data issues. This approach consists in the integration of data from different heterogeneous sources via RDF and identifying contradicting data automatically with SPARQL. Librarians can inspect the contradicting data fields, choose the correct data, and thus semi-automatically correct the contradiction. This contribution describes the approach, which is implemented as a 5-step workflow using linked data and Python. We discuss how we use the workflow to improve the correctness of the data used in the BELTRANS project and the wider applicability of the workflow within the National Library to improve the completeness of our catalog with respect to legal deposit. Since the expertise of librarians is needed to interpret identified data contradictions, the next step is to improve the usability of our prototypical solution.
---
# A LITL more quality: improving the correctness and completeness of library catalogs with a librarian-in-the-loop linked data workflow
[[Sven Lieber]], [[Ann Van Camp]], [[Hannes Lowagie]]

Traditionally, a library maintains both bibliographic data about publications and authority data about publication contributors such as authors or publishers. At the Royal Library of Belgium ([[KBR]]), we currently maintain more than 900,000 authority records about persons and metadata records of over 3.5 million publications. As an authoritative data source we are expected to have correct and complete data. In contrast to syntactical data quality issues – which can be detected automatically – issues regarding the correctness of data or completeness of the catalogue often require semantic checks, e.g., if the correct [[ISBN]] is used and if the nationality of the contributor is correct. However, the amount of Belgian cultural heritage data makes manual quality checks very time-consuming.
Within the [[BELTRANS]] [[project]] which studies Intra-Belgian book translation flows of publications based on metadata (who?, when?, where?), we developed an approach to support librarians in the detection and correction of semantic data issues. This approach consists in the integration of data from different heterogeneous sources via [[RDF]] and identifying contradicting data automatically with [[SPARQL]]. Librarians can inspect the contradicting data fields, choose the correct data, and thus semi-automatically correct the contradiction. This contribution describes the approach, which is implemented as a 5-step workflow using [[linked data]] and [[Python]]. We discuss how we use the workflow to improve the correctness of the data used in the BELTRANS project and the wider applicability of the workflow within the National Library to improve the completeness of our catalog with respect to legal deposit. Since the expertise of librarians is needed to interpret identified data contradictions, the next step is to improve the usability of our prototypical solution.
