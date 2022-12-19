## A BERT Baseline for the Natural Questions

Paper - [https://arxiv.org/pdf/1901.08634.pdf](https://arxiv.org/pdf/1901.08634.pdf)

In this notebook, we implement the paper with slight changes to the dataset.

There is no question type, so the training instance is of tuple (c, s, e) where c is a context of 512 wordpiece ids (including question, document tokens and markup), s, e ∈ {0, 1, . . . , 511} are inclusive indices pointing to the start and end of the target answer span. 

There is no long answer in the dataset and the complexity of this baseline model is reduced by always outputting a single short answer as prediction.

Video link - [https://drive.google.com/file/d/1aaeuDHBq2jxcWgbiIvtQR17drbn6wpuE/view?usp=share_link](https://drive.google.com/file/d/1aaeuDHBq2jxcWgbiIvtQR17drbn6wpuE/view?usp=share_link)