This repository contains the dataset for for the paper [Towards Reversal-Based Textual Data Augmentation for NLI Problems with Opposable Classes](https://www.aclweb.org/anthology/2020.nli-1.2/), which is devoted to some preliminary experiments about possibilities of textual data augmentation, exploiting "opposable" classes. 

The dataset covers a scenario where an English sentence is used to derive a statement in a proprietary expression language. The file contains 851 instances and was gathered using Amazon Mechanical Turk (for more details please see the paper). There are three fields:

- **Question**: a logical statement presented to a turker. Had to be rephrased using a single English sentence.
- **Answer**: English sentence provided by a turker (output of HITs), a rephrasing of Question.
- **Class**: class of a logical statement (one of six).

If you use this dataset, please cite the following paper:
```
@inproceedings{tarasov-2020-towards,
    title = "Towards Reversal-Based Textual Data Augmentation for {NLI} Problems with Opposable Classes",
    author = "Tarasov, Alexey",
    booktitle = "Proceedings of the First Workshop on Natural Language Interfaces",
    year = "2020",
    publisher = "Association for Computational Linguistics",
    pages = "11--19",
}
```
If you have any question about the data, feel free to raise a github issue or drop me an email. Thanks!