# Summary

The treebank is a corpus of Kurmanji Kurdish. It contains fiction and encyclopaedic texts in
roughly equal measure. It has been annotated natively in accordance with the UD annotation scheme.

# Introduction

This is a Kurmanji (Northern Kurdish) treebank developed with the UD framework. It consists of a Sherlock Holmes story, "The Adventure of the Speckled Band", translated in 1944 by Celadet Bedirxan in the magazine Ronahi, and sentences from the Kurmanji Wikipedia.

# Acknowledgments

If you use this treebank in your work, please cite:

@inproceedings{gokirmak:2017,
    author = {Memduh Gökırmak and Francis M. Tyers},
    title = {A Dependency Treebank for Kurmanji Kurdish},
    booktitle = {Proceedings of the Fourth International Conference on Dependency Linguistics (DepLing, 2017)},
    pages = {64--73},
    year = 2017
}

# Changelog

* 2025-11-15 v2.17
  * Repository renamed from UD_Kurmanji-MG to UD_Northern_Kurdish-Kurmanji.
* 2022-11-15 v2.11
  * Fixed validation errors.
* 2021-05-15 v2.8
  * The oblique case is labeled Case=Acc following the UD guidelines.
  * Removed undocumented relation subtype case:circ (2 occurrences).
  * Relation nmod:dat changed to obl:dat (the parent is usually verb).
  * Fixed non-projective punctuation.
* 2018-04-15 v2.2
  * Repository renamed from UD_Kurmanji to UD_Kurmanji-MG.
* 2017-11-15 v2.1
  * First official release after it was used as a surprise dataset in the
    CoNLL 2017 shared task.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v2.1
License: CC BY-SA 4.0
Includes text: yes
Genre: fiction wiki
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Gökırmak, Memduh; Tyers, Francis
Contributing: elsewhere
Contact: memduhg@gmail.com ftyers@hse.ru
Paragraphs to web: 1
===============================================================================
</pre>
