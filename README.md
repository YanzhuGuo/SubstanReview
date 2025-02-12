# SubstanReview

The SubstanReview dataset consists of 550 annotated peer reviews (440 in the train set and 110 in the test set). It is released in the json line format with two different fields:

"review" includes the textual content of the peer review.

"label" includes the annotated spans of claim-evidence pairs. A claim span and an evidence span forms a pair if they are assigned with the same number. For example, "Jus_neg_1" is linked to "Eval_neg_1".


### Citation
```
@inproceedings{guo-etal-2023-automatic,
    title = "Automatic Analysis of Substantiation in Scientific Peer Reviews",
    author = "Guo, Yanzhu  and
      Shang, Guokan  and
      Rennard, Virgile  and
      Vazirgiannis, Michalis  and
      Clavel, Chlo{\'e}",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-emnlp.684/",
    doi = "10.18653/v1/2023.findings-emnlp.684",
    pages = "10198--10216"
}
```
