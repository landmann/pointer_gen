# Pointer Generator Model

_This repository contains modified code for the ACL 2017 paper *[Get To The Point: Summarization with Pointer-Generator Networks](https://arxiv.org/abs/1704.04368)*. For an intuitive overview of the original paper, read the [blog post](http://www.abigailsee.com/2017/04/16/taming-rnns-for-better-summarization.html).  For a beautiful documentation of how to run the original model, please refer to the [code for the paper](https://github.com/abisee/pointer-generator). The Python 3 version of the code that inspired this repo can be found [here](https://github.com/becxer/pointer-generator/)._

### What's in it for me?

The goal of this repo is to serve as a tutorial for people just starting out with deep learning.  It is certainly not exhaustive, but it's how I learned some TensorFlow. This tutorial uses one particular encoder-decoder network whose primary use is for summarizing text documents.  The idea, however, is for the writing to be general enough and flexible so that the key points are applicable to any paper or code.

You'll certainly get the most out of this notebook if you have some prior coding experience and know a bit of deep learning theory.  It goes step by step about what papers I read and how I ended up understanding this model's ins and outs.  Not only that, but also be able to tweak the model to explore your own ideas. If you have feedback or other ways you'd like to alter the model but don't know how to, please add your idea to the *Issues* handle and I'll address it at some point!


### Table of Contents

0. Before You Start

   _Some Words_

1. Getting the Code to Run
   
   _Understand parameters and the types of outputs you'll get._

2. Exploring Visualization Tools

   _How to see exactly what your model is outputting_

2. Modifying our own Dataset

   _Helps you understand the input and output formats, as well as the limitations the model presents given your own data._

3. Using Pre-Trained Word Embeddings

   _Changing the embedding layer is a simple way to adapt your model without it breaking easily. Usually boosts performance!_

4. Shuffling Sentences and Removing Words

   _Will help you understand what exactly is being processed by the model._

5. Teacher Forcing

   _A simple techinque, it lets the model deviate from the desired output just a little bit._

6. Adding Mixture Coefficient to the Tranining

   _Implementing a method from another paper. Involves changing the beam decoder_

7. Adding Another Attention Layer given an Input

   _Delves into the attention module_

8. Using Target Embedding as a Loss Function

   _Simple tweak that delves into the nuances of differentaible components_

9. Reinforcement Learning Loss Function

   _Implementing another paper's methods into this model._

### Before You Start

In order to understand what you're getting into, I recommend you read a few papers. The first one, and most obvious one, is the one directly coming from the code's author, which comes with a beautifully written blog post, which you can find [here](http://www.abigailsee.com/2017/04/16/taming-rnns-for-better-summarization.html).  Another point to understand is a little bit about TensorFlow, but truthfully I knew very little as well when I dove into this paper first, so it's not necessary. Hopefully doing these modifications helps on this front.

### Getting the Code to Run










