# [ACL'19 (long)] GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction
A **PyTorch** implementation of GraphRel

[Project](https://tsujuifu.github.io/projs/acl19_graph-rel.html) | [Paper](https://tsujuifu.github.io/pubs/acl19_graph-rel.pdf) | [Poster](imgs/poster.png)

<img src='imgs/result.png' width='85%' />

## Overview
GraphRel is an implementation of <br> 
"[GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction](https://tsujuifu.github.io/pubs/emnlp18_lstm-shuttle.pdf)" <br>
[Tsu-Jui Fu](http://tsujuifu.github.io/), [Peng-Hsuan Li](http://jacobvsdanniel.github.io/), and [Wei-Yun Ma](http://www.iis.sinica.edu.tw/pages/ma/) <br>
in Annual Meeting of the Association for Computational Linguistics (**ACL**) 2019 (long)

<img src='imgs/overview.png' width='80%' />

## Requirements
This code is implemented under **Python3** and [PyTorch](https://pytorch.org). <br>
Following libraries are also required:
+ [PyTorch](https://pytorch.org) >= 0.4
+ [spaCy](https://spacy.io)

## Usage
We use [spaCy](https://spacy.io/) as **pre-trained word embedding** and **dependency parser**.

## Resources
+ NYT Dataset
+ WebNLG Dataset

## Citation
```
@inproceedings{fu2019graph-rel, 
  author = {Tsu-Jui Fu and Peng-Hsuan Li and Wei-Yun Ma}, 
  title = {GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extractionn}, 
  booktitle = {Annual Meeting of the Association for Computational Linguistics (ACL)}, 
  year = {2019} 
}
```

## Acknowledgement
+ [copy_re](https://github.com/xiangrongzeng/copy_re)
