# WMT-Biomed-Test (fr-en)

This repository contains refactored versions of the testsets used in the Bio-Medical translation shared task for the years 
[2016](https://statmt.org/wmt16/biomedical-translation-task.html),
[2017](https://statmt.org/wmt17/biomedical-translation-task.html),
[2018](https://statmt.org/wmt18/biomedical-translation-task.html),
[2019](https://statmt.org/wmt19/biomedical-translation-task.html),
[2020](https://statmt.org/wmt20/biomedical-translation-task.html)
(French-English). The documents have been downloaded from the [main datasource](https://github.com/biomedical-translation-corpora/corpora), then realigned at the document and the sentence level so as to provide more suitable format for MT evaluations, which typically expect sentence-aligned source target pairs. 

Document Level tests are aligned test sets at the 'topic' level. One empty line indicates topic boundary and two empty lines are used to mark document boundaries.

Sentence level test sets are simpler sentence-aligned versions of test sets available in the Document Level test sets folder.

Train data includes 6 bio-medical corpora tagged with section information as detailed in the following article:


Sadaf Abdul Rauf and François Yvon, "Translating scientific abstracts in the bio-medical domain with structure-aware models", Computer Speech & Language, 
Volume 87, 2024, ISSN 0885-2308, https://doi.org/10.1016/j.csl.2024.101623.

(https://www.sciencedirect.com/science/article/pii/S0885230824000068)

Abstract: Machine Translation (MT) technologies have improved in many ways and generate usable outputs for a growing number of domains and language pairs. Yet, most sentence based MT systems struggle with contextual dependencies, processing small chunks of texts, typically sentences, in isolation from their textual context. This is likely to cause systematic errors or inconsistencies when processing long documents. While various attempts are made to handle extended contexts in translation, the relevance of these contextual cues, especially those related to the structural organization, and the extent to which they affect translation quality remains an under explored area. In this work, we explore ways to take these structural aspects into account, by integrating document structure as an extra conditioning context. Our experiments on biomedical abstracts, which are usually structured in a rigid way, suggest that this type of structural information can be useful for MT and document structure prediction. We also present in detail the impact of structural information on MT output and assess the degree to which structural information can be learned from the data.
Keywords: Neural machine translation; Document-level machine translation; Bio-medical natural language processing


