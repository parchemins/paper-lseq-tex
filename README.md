# LSEQ: an Adaptive Structure for Sequences in Distributed Collaborative Editing

<i>Keywords: conflict-free replicated data type; distributed collaborative
editing; distributed documents; document authoring tools and systems; real-time
editing</i>

<i>Authors: Brice Nédelec, Pascal Molli, Achour Mostefaoui, Emmanuel
Desmontils</i>

Distributed collaborative editing systems allow users to work distributed in
time, space and across organizations. Trending distributed collaborative
editors such as Google Docs, Etherpad or Git have grown in popularity over the
years. A new kind of distributed editors based on a family of distributed data
structure replicated on several sites called Conflict-free Replicated Data Type
(CRDT for short) appeared recently. This paper considers a CRDT that represents
a distributed sequence of basic elements that can be lines, words or characters
(sequence CRDT). The possible operations on this sequence are the insertion and
the deletion of elements. Compared to the state of the art, this approach is
more decentralized and better scales in terms of the number of
participants. However, its space complexity is linear with respect to the total
number of inserts and the insertion points in the document. This makes the
overall performance of such editors dependent on the editing behaviour of
users. This paper proposes and models LSEQ, an adaptive allocation strategy for
a sequence CRDT. LSEQ achieves in the average a sub-linear spatial-complexity
whatever is the editing behaviour. A series of experiments validates LSEQ
showing that it outperforms existing approaches.


## Available at

<ul>
  <li> [HAL](https://hal.archives-ouvertes.fr/hal-00921633)</li>
  <li> [ACM Digital Library](http://dl.acm.org/citation.cfm?id=2494278&dl=ACM&coll=DL&CFID=492734669&CFTOKEN=59297952) </li>
</ul>

## BibTeX

```
@inproceedings{Nedelec:2013:LAS:2494266.2494278,
  author = {N{\'e}delec, Brice and Molli, Pascal and Mostefaoui,
            Achour and Desmontils, Emmanuel},
  title = {LSEQ: An Adaptive Structure for Sequences in Distributed
           Collaborative Editing},
  booktitle = {Proceedings of the 2013 ACM Symposium on Document Engineering},
  series = {DocEng '13},
  year = {2013},
  isbn = {978-1-4503-1789-4},
  location = {Florence, Italy},
  pages = {37--46},
  numpages = {10},
  url = {http://doi.acm.org/10.1145/2494266.2494278},
  doi = {10.1145/2494266.2494278},
  acmid = {2494278},
  publisher = {ACM},
  address = {New York, NY, USA},
  keywords = {conflict-free replicated data types, distributed collaborative
              editing, distributed documents, document authoring tools and
              systems, real-time editing}
} 
```

## Acknowledgments

This work was partially funded by the French ANR project ConcoRDanT
([ANR-10-BLAN-0208](http://www.agence-nationale-recherche.fr/?Projet=ANR-10-BLAN-0208)).