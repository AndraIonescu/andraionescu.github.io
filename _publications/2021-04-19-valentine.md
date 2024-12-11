---
title: "Valentine: Evaluating matching techniques for dataset discovery"
collection: publications
permalink: /publication/valentine
excerpt: 'Data scientists today search large data lakes to discover and integrate datasets. In order to bring together disparate data sources, dataset discovery methods rely on some form of schema matching: the process of establishing correspondences between datasets. Traditionally, schema matching has been used to find matching pairs of columns between a source and a target schema. However, the use of schema matching in dataset discovery methods differs from its original use.'
date: 2021-04-19
venue: 'ICDE'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9458921'
authors: 'Christos Koutras, George Siachamis, Andra Ionescu, Kyriakos Psarakis, Jerry Brons, Marios Fragkoulis, Christoph Lofi, Angela Bonifati, Asterios Katsifodimos'
---

In this paper, we aim to rectify the problem of evaluating
the effectiveness and efficiency of schema matching methods for
the specific needs of dataset discovery. To this end, we propose
Valentine, an extensible open-source experiment suite to execute
and organize large-scale automated matching experiments on tabular data. Valentine includes implementations of seminal schema
matching methods that we either implemented from scratch
(due to absence of open source code) or imported from open
repositories. The contributions of Valentine are: i) the definition
of four schema matching scenarios as encountered in dataset
discovery methods, ii) a principled dataset fabrication process
tailored to the scope of dataset discovery methods and iii) the
most comprehensive evaluation of schema matching techniques to
date, offering insight on the strengths and weaknesses of existing
techniques, that can serve as a guide for employing schema
matching in future dataset discovery methods.

<ul>
    <li> 
        <a href="https://delftdata.github.io/valentine/" target="_blank"><i class="fa-solid fa-globe"></i> Project Website</a>
    </li>
</ul>


- Bibtex: 
```
@inproceedings{koutras2021valentine,
  title={Valentine: Evaluating matching techniques for dataset discovery},
  author={Koutras, Christos and Siachamis, George and Ionescu, Andra and Psarakis, Kyriakos and Brons, Jerry and Fragkoulis, Marios and Lofi, Christoph and Bonifati, Angela and Katsifodimos, Asterios},
  booktitle={2021 IEEE 37th International Conference on Data Engineering (ICDE)},
  pages={468--479},
  year={2021},
  organization={IEEE}
}
```