# Summary

UD EWT treebank consists of different genres of new media. The treebank contains 7,190 trees, 90,585 tokens.


# Introduction

Estonian Web Treebank UD v2.16 consists of four parts. Its older part (1,662 trees, v2.4) is a converted version of the Estonian Web Treebank (EWT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of different genres of new media. 
The second part (1,495 trees, v2.6) consists of internet forum texts and has been annotated using [Stanza parser](https://stanfordnlp.github.io/stanza/), followed by manual post-editing.
The third part (v2.8) has been annnotated in the same way. It consists of users' feedbacks to news about Covid19 pandemic in 2020-2021 (~12,725 tokens).
The fourth part consists of different forum texts (reddit, military, gardening, cars). In addition to standard ud annotation, annotation of named entiites has been added to MISC-field (NE=B-Type or NE=I-Type, there TYPE stands for PER (person), ORG (organisation), LOC (location), GEP (geopolitical name), EVENT (events), PROD (product), MUU (other) or UNK (unknown)).

The treebank consists of 7,190 trees, 90,585 tokens. As for enhanced dependencies, the empty nodes for missing predicates have been added, and the relative pronoun is attached to its antecedent with the relation 'ref', also other enhanced dependencies have been added since version 2.13

The treebank has been divided  to train, test and dev parts as 67,431; 13,152 and 10,002 tokens respectively.

The treebank covers unedited new media texts.


# Acknowledgments

We wish to thank developers of [Udapi](http://udapi.github.io/), [UD Annotatrix](https://github.com/jonorthwash/ud-annotatrix), and [ConlluEditor](https://github.com/Orange-OpenSource/conllueditor) tools.

This work was financed by the [National Programme for Estonian Language Technology](https://www.keeletehnoloogia.ee/en?set_language=en) and Estonian Ministery of Education and Research (grant 20-56 IUT20-56 "Computational models for Estonian").

# References

* Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Eleri Aedmaa, Riin Kirt, Dage Särg.  2014.
  [Estonian Dependency Treebank and its annotation scheme](http://tlt13.sfs.uni-tuebingen.de/tlt13-proceedings.pdf). In: Proceedings of the 13th Workshop on Treebanks and Linguistic Theories (TLT13), pp. 285–291, ISBN 978-3-9809183-9-8, Tübingen, Germany.
* Kadri Muischnek, Kaili Müürisep, Dage Särg. 2019. [CG Roots of UD Treebank of Estonian Web Language](http://www.ep.liu.se/ecp/168/006/ecp19168006.pdf). In Proceedings of the NoDaLiDa 2019 Workshop on Constraint Grammar-Methods, Tools and Applications, pp. 23-26, Turku, Finland
* Kadri Muischnek, Kaili Müürisep. 2023. [Named Entity layer in Estonian UD treebanks](https://openreview.net/pdf?id=mo1p--2vbq). In Proceedings NoDaLiDa 2023.
 
# Changelog

* UD v2.17: a few minor fixes, mostly related to obl:agent dependencies.
* UD v2.16: ExtPos feature added, a few minor fixes.
* UD v2.15: annotation of foreign words and determiners fixed, agent adverbials have special tag obl:agent.
* UD v2.13: enhanced dependencies added.
* UD v2.12: many errors fixed in the NE annotation, minor other fixes.
* UD v2.11: new texts added to the training corpus (12,358 tokens), added annotation for named entities.
* UD v2.10: new texts added to the training corpus (5,472 words, 462 trees), fixed errors of goeswith annotation.
* UD v2.8: new texts added to the training corpus, annotation of numerals modified, enhanced annotation of relative pronouns added
* UD v2.7: new texts, extra annotation for typos, better tokenization and sentence segmentation
* UD v2.6: new internet forum texts (~15,000 tokens), 0-nodes in clauses.
* UD v2.4: automatic conversion from CG, manual reannotation.

<pre>
=== Machine-readable metadata =================================================
Documentation status: stub
Data source: semi-automatic
Data available since: UD v2.4
License: CC BY-NC-SA 4.0
Includes text: yes
Parallel: no
Genre: blog web social
Lemmas: converted from manual
UPOS: converted from manual
XPOS: converted from manual
Features: converted from manual
Relations: converted from manual
Contributing: here
Contributors: Muischnek, Kadri; Müürisep, Kaili; Puolakainen, Tiina; Särg, Dage; Eiche, Sandra; Rääbis, Andriela
Contact: kadri.muischnek@ut.ee, kaili.muurisep@ut.ee
===============================================================================
</pre>
