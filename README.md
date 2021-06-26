# Transformers-For-Negation-and-Speculation
1. Transformers_for_Negation_and_Speculation.ipynb:
  > This is the code for the following papers:
* [NegBERT: A Transfer Learning Approach for Negation Detection and Scope Resolution](https://arxiv.org/abs/1911.04211) (Published at LREC 2020)
* [Resolving the Scope of Speculation and Negation using Transformer-Based Architectures](https://arxiv.org/abs/2001.02885)
2. Multitask_Learning_of_Negation_and_Speculation.ipynb:
  > This is the code for the following paper:
* [Multitask Learning of Negation and Speculation using Transformers](https://www.aclweb.org/anthology/2020.louhi-1.9.pdf) (Published at LOUHI 2020)

Code has been utilized from the following sources:
* The starter code was taken from [this article on Named Entity Recognition with Bert](https://www.depends-on-the-definition.com/named-entity-recognition-with-bert/).  
* To be able to implement XLNetForTokenClassification and RobertaForTokenClassification for the [Transformers library by Huggingface](https://github.com/huggingface/transformers), some code was copy-pasted from that code base.  
* The implementation of Early Stopping for PyTorch was adapted from [Bjarten's implementation(GitHub)](https://github.com/Bjarten/early-stopping-pytorch/blob/master/pytorchtools.py).

The colab notebook can be executed directly from Google Colaboratory.

Datasets:
1. [BioScope Corpus](https://rgai.sed.hu/node/105)
2. [Sherlock (*sem 2012 Shared Task)](https://www.clips.uantwerpen.be/sem2012-st-neg/)
3. [SFU Review Corpus](https://www.sfu.ca/~mtaboada/SFU_Review_Corpus.html)

Contributors: [Aditya Khandelwal](https://github.com/adityak6798), [Benita Kathleen Britto](https://github.com/benitakbritto)
