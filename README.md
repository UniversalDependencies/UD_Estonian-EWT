# Summary

UD EWT treebank consists of different genres of new media. The treebank contains 3,157 trees, 43,084 tokens.


# Introduction

Estonian Web Treebank UD v2.6 consists of two parts. Its older part (1,662 trees, v2.4) is a converted version of the Estonian Web Treebank (EWT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of different genres of new media. 
The newer part (1,495 trees, v2.6) consists of internet forum texts and has been annotated using [Stanza parser](https://stanfordnlp.github.io/stanza/), followed by manual post-editing.

The treebank consists of 3,157 trees, 43,084 tokens. As for enhanced dependencies, the empty nodes for missing predicates have been added, but there are no other types of enhanced dependencies in this version.

The treebank has been divided  to train, test and dev parts as 21,795; 13133 and 8156 tokens respectively.

The treebank covers unedited new media texts.


# Acknowledgments

We wish to thank developers of [Udapi](http://udapi.github.io/), [UD Annotatrix](https://github.com/jonorthwash/ud-annotatrix), and [ConlluEditor](https://github.com/Orange-OpenSource/conllueditor) tools.

This work was financed by the [National Programme for Estonian Language Technology](https://www.keeletehnoloogia.ee/en?set_language=en) and Estonian Ministery of Education and Research (grant 20-56 IUT20-56 "Computational models for Estonian").

# References

* Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Eleri Aedmaa, Riin Kirt, Dage Särg.  2014.
  [Estonian Dependency Treebank and its annotation scheme](http://tlt13.sfs.uni-tuebingen.de/tlt13-proceedings.pdf). In: Proceedings of the 13th Workshop on Treebanks and Linguistic Theories (TLT13), pp. 285–291, ISBN 978-3-9809183-9-8, Tübingen, Germany.
* Kadri Muischnek, Kaili Müürisep, Dage Särg. 2019. [CG Roots of UD Treebank of Estonian Web Language](http://www.ep.liu.se/ecp/168/006/ecp19168006.pdf). In Proceedings of the NoDaLiDa 2019 Workshop on Constraint Grammar-Methods, Tools and Applications, pp. 23-26, Turku, Finland
 
# Changelog

* UD v2.6: new internet forum texts (~15,000 tokens), 0-nodes in clauses.
* UD v2.4: automatic conversion from CG, manual reannotation.

<pre>
=== Machine-readable metadata =================================================
Documentation status: stub
Data source: semi-automatic
Data available since: UD v2.4
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: blog web social
Lemmas: converted from manual
UPOS: converted from manual
XPOS: converted from manual
Features: converted from manual
Relations: converted from manual
Contributing: here
Contributors: Muischnek, Kadri; Müürisep, Kaili; Puolakainen, Tiina; Särg, Dage
Contact: kadri.muischnek@ut.ee, kaili.muurisep@ut.ee
===============================================================================
</pre>
