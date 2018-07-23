# Training a Neural Network in a Low-Resource Setting on Automatically Annotated Noisy Data

### Abstract
Manually labeled corpora are expensive to create and often not available for low-resource languages or domains. Automatic labeling approaches are an alternative way to obtain labeled data in a quicker and cheaper way. However, these labels often contain more errors which can deteriorate a classifier's performance when trained on this data. We propose a noise layer that is added to a neural network architecture. This allows modeling the noise and train on a combination of clean and noisy data. We show that in a low-resource NER task we can improve performance by up to 35\% by using additional, noisy data and handling the noise.

### Resources

- **Paper**: https://arxiv.org/abs/1807.00745 (latest version) or http://aclweb.org/anthology/W18-3402
- **Slides**: See content of this repository
- **Poster**: See content of this repository
- **Code**: Please contact the authors at *mail at michael-hedderich .de*

### BibTex
```
@InProceedings{W18-3402,
  author = 	"Hedderich, Michael A. and Klakow, Dietrich",
  title = 	"Training a Neural Network in a Low-Resource Setting on Automatically Annotated Noisy Data",
  booktitle = 	"Proceedings of the Workshop on Deep Learning Approaches for Low-Resource NLP",
  year = 	"2018",
  publisher = 	"Association for Computational Linguistics",
  pages = 	"12--18",
  location = 	"Melbourne",
  url = 	"http://aclweb.org/anthology/W18-3402"
}
```
