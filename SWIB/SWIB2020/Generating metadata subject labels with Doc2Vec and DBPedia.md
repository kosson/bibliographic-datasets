---
alias: SWIB
type: presentation
event: SWIB 2020
year: "2020"
partof: "Authorities"
tags:
  - "#metadata"
  - "#unsupervised/learning"
  - "#clusters"
  - "#labeling"
  - "#Doc2Vec"
  - "#DBPedia"
  - "#corpora"
  - "#unlabeled/clustering"
  - "#metadata/generation"
  - '#subject/labels'
  - '#subject/indexing'
title: Generating metadata subject labels with Doc2Vec and DBPedia
alt: ''
resources:
  - "https: //swib.org/swib20/slides/03-05-harper.pdf"
  - 'https: //youtu.be/nIjP5oooP_k'
author:
  - Charlie Harper
abstract: Previous approaches to metadata creation using unsupervised learning have often centered on generating document clusters, which then require manual labeling. Common approaches, such as topic modelling with Latent Dirichlet Allocation, are also limited by the need to determine the number of clusters prior to training. While this is useful for finding underlying relationships in corpora, unlabeled clustering does not provide an ideal way to generate metadata. In this presentation, I examine one way that unsupervised machine learning and linked data can be employed to generate rich metadata labels for textual resources and thereby improve resource discovery. To generate document-specific metadata, I build high-dimensional vectors using the doc2vec algorithm on DBPedia entries. DBPedia regularly collects millions of pages from wikipedia, including a unique label, an abstract, and extensive information on the semantic links between pages. While abstracts and labels can be extremely specific and are unlikely to provide broadly usable metadata tags, the linked nature of this dataset provides a valuable way to improve this. Using predicates like dct:subject and skos:broader, page vectors can be averaged together to encode higher conceptual levels of information that are labelled by a unique subject or idea. By then vectorizing an unseen document’s abstract, a k-d search tree can quickly locate the nearest subjects in vector space and suggest what labels should be assigned to a document. To explore its efficacy, this tagging approach is applied to a corpus of dissertations and theses published at Ohio universities and colleges. Methods for visualizing the tagged corpus are finally explored to determine if the linked nature of the subject tags may allow users to visually discover related texts in a more natural, less constrained way.
---
# Generating metadata subject labels with Doc2Vec and DBPedia

[[Charlie Harper]]

Previous approaches to metadata creation using [[unsupervised learning]] have often centered on generating document clusters, which then require manual labeling. Common approaches, such as topic modelling with Latent Dirichlet Allocation, are also limited by the need to determine the number of clusters prior to training. While this is useful for finding underlying relationships in corpora, [[unlabeled clustering]] does not provide an ideal way to generate [[metadata]]. In this presentation, I examine one way that unsupervised machine learning and linked data can be employed to generate rich metadata labels for textual resources and thereby improve resource discovery.
To generate document-specific metadata, I build high-dimensional vectors using the doc2vec algorithm on DBPedia entries. DBPedia regularly collects millions of pages from wikipedia, including a unique label, an abstract, and extensive information on the semantic links between pages. While abstracts and labels can be extremely specific and are unlikely to provide broadly usable metadata tags, the linked nature of this dataset provides a valuable way to improve this. Using predicates like dct:subject and skos:broader, page vectors can be averaged together to encode higher conceptual levels of information that are labelled by a unique subject or idea. By then vectorizing an unseen document’s abstract, a k-d search tree can quickly locate the nearest subjects in vector space and suggest what labels should be assigned to a document. To explore its efficacy, this tagging approach is applied to a corpus of dissertations and theses published at Ohio universities and colleges. Methods for visualizing the tagged corpus are finally explored to determine if the linked nature of the subject tags may allow users to visually discover related texts in a more natural, less constrained way.
