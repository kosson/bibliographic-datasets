---
alias: SWIB
type: presentation
event: SWIB 2022
year: "2022"
partof: "Machine Learning"
tags:
  - "#BERT"
  - "#bibliographic/data"
  - "#K10plus"
  - "#mBERT"
  - "#Support/Vector/Machine/classifier"
  - "#library/classification/system"
  - "#class/prediction"
  - "#tokenizer"
title: Multilingual BERT for library classification in Romance languages using Basisklassifikation
alt: ''
resources:
  - "https: //swib.org/swib22/slides/20221202_1236_ct_mBERT-Basisklassifikation.pdf"
  - 'https: //youtu.be/7fmvYzlf9oM'
author:
  - José Calvo Tello
  - Enrique Manjavacas
  - Susanne Al-Eryani
abstract: "We apply the multilingual version of the language model BERT (mBERT) to predict classes from the library classification system Basisklassifikation (BK). We frame the present task as a multi-label classification problem, where each input instance (a library record) must be assigned at least one class from the BK. As input, we only use data from the catalogue, we do not use the full text of the publications. Three feature sets are considered: title only, bibliographic data only, and extended bibliographic data. We apply two algorithms: mBERT, which we fine-tune using raw text from different metadata fields as input. We also train a multi-label Support Vector Machine classifier with a vector based on the tokenizer of mBERT. We decided to work with records from Romance Studies because it challenges the perspective of considering only one or only a few languages, such as in national libraries. The dataset contains 189,134 library records associated with Romance Studies from the catalogue K10plus. The general results for the different approaches yield micro F1-scores between 0.6 and 0.8 (macro F1-scores between 0.2 and 0.4), with better performance for mBERT as classifier. In this presentation we will explore how these results are influenced by factors such as the language, specific classes, or the number of records per class. This is a promising approach for the generation of suggestions which should be considered by subject specialists."
---
# Multilingual BERT for library classification in Romance languages using Basisklassifikation
[[José Calvo Tello]], [[Enrique Manjavacas]], [[Susanne Al-Eryani]]

We apply the multilingual version of the language model [[BERT]] ([[mBERT]]) to predict classes from the library classification system [[Basisklassifikation]] ([[BK]]). We frame the present task as a multi-label classification problem, where each input instance (a library record) must be assigned at least one class from the BK. As input, we only use data from the catalogue, we do not use the full text of the publications. Three feature sets are considered: title only, bibliographic data only, and extended bibliographic data. We apply two algorithms: mBERT, which we fine-tune using raw text from different metadata fields as input. We also train a multi-label [[Support Vector Machine]] [[classifier]] with a vector based on the [[tokenizer]] of mBERT.
We decided to work with records from Romance Studies because it challenges the perspective of considering only one or only a few languages, such as in national libraries. The dataset contains 189,134 library records associated with Romance Studies from the catalogue [[K10plus]].
The general results for the different approaches yield micro F1-scores between 0.6 and 0.8 (macro F1-scores between 0.2 and 0.4), with better performance for mBERT as classifier. In this presentation we will explore how these results are influenced by factors such as the language, specific classes, or the number of records per class. This is a promising approach for the generation of suggestions which should be considered by subject specialists.
