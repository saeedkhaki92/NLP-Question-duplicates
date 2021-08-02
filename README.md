# NLP-Question-duplicates

This project explores Siamese networks applied to natural language processing to find if two questions are duplicates or not. The project uses Trax deep learning library for implementation.


![Alt Text](https://github.com/saeedkhaki92/NLP-Question-duplicates/blob/main/meme.png)


## Getting Started

### Dependencies

Following packages should be installed on python 3:

- Trax
- numpy
- random

<a href="https://github.com/google/trax" target="_blank">Trax</a> is an end-to-end library for deep learning that focuses on clear code and speed. It is actively used and maintained in the Google Brain team. It is faster than Tensorflow and Pytorch and also the codes are more clear. It also supprts both TPUs and GPUs.




## Dataset

We will be using the Quora question answer dataset to build a model that could identify similar questions. This is a useful task because you don't want to have several versions of the same question posted. Several times when teaching I end up responding to similar questions on piazza, or on other community forums. 


### Model

A Siamese network is a neural network which uses the same weights while working in tandem on two different input vectors to compute comparable output vectors.The Siamese network you are about to implement looks like this:


![Alt Text](https://github.com/saeedkhaki92/NLP-Question-duplicates/blob/main/siamese.png)



## Instructions

You can train the model from scrath using the Google Colab notebooks. Please use `Q_duplicate_trax.ipynb` for Trax version.

## Results

I trained the model for several epochs and the validation accuracy is around 70%.
