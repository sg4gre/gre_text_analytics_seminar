Introduction to text analytics seminar.

Author: Dr Stef Garasto.

Licence: GPLv3.

Python script to reproduce (approximately and partially) the paper "Analyzing Gender Bias within Narrative Tropes" by Gala et al. (2020)

The goal is to show some useful text analytics techniques in context.

Specifically, we will see:

- some cleaning steps and a bit about regular expressions.
- extract and plot top terms in a collection of documents (using a count-based Bag of Words model).
- match specific keywords in a text.
- a bit about approximate matching of specific keywords in a text (using word embeddings).
- topic modelling using Latent Dirichlet Allocation.

These techniques are applied to try and quantify the binary "genderedness" of tropes and topics within those tropes.


The original paper whose work is reproduced should be cited as follows:

```
@inproceedings{gala-etal-2020-analyzing,
    title = "Analyzing Gender Bias within Narrative Tropes",
    author = "Gala, Dhruvil  and
      Khursheed, Mohammad Omar  and
      Lerner, Hannah  and
      O{'}Connor, Brendan  and
      Iyyer, Mohit",
    booktitle = "Proceedings of the Fourth Workshop on Natural Language Processing and Computational Social Science",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.nlpcss-1.23",
    doi = "10.18653/v1/2020.nlpcss-1.23",
    pages = "212--217",
    abstract = "Popular media reflects and reinforces societal biases through the use of tropes, which are narrative elements, such as archetypal characters and plot arcs, that occur frequently across media. In this paper, we specifically investigate gender bias within a large collection of tropes. To enable our study, we crawl tvtropes.org, an online user-created repository that contains 30K tropes associated with 1.9M examples of their occurrences across film, television, and literature. We automatically score the {``}genderedness{''} of each trope in our TVTROPES dataset, which enables an analysis of (1) highly-gendered topics within tropes, (2) the relationship between gender bias and popular reception, and (3) how the gender of a work{'}s creator correlates with the types of tropes that they use.",
}
```
