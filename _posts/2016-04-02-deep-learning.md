---
layout: post
title:  "Deep Learning"
date:   2016-05-21
---

There has been a lot of excitement recently about Deep Learning, which is
the most recent rebranding of neural networks. The essence of Deep Learning
seems to be the automatic learning of internal representations,
which means that features do not need to be handcoded. This is powerful
as we do not have to know much about the domain of interest a priori. If
you have learned some statistics you might be uncomfortable with this lack
of priors because of the bias-variance tradeoff (or
the no free lunch theorem).
If we do not know much about the domain of interest, then surely
we should not be able to interpolate/extrapolate correctly? However, with
Deep Learning, we do have a prior, which is that the data or task
has some kind of hierarchical and layered structure. And it seems this is
an appropriate prior for real-world tasks (this kind of empiricism seems
to be one of the main differences between statistics and machine learning,
but that is another story). Also, since neural networks are
composed of many smaller components, it is possible to hand-engineer some
specific structural priors. An example would be using convolutional networks
to implement translation-invariance in computer vision.

Representation learning through some kind of architectural hierarchy
is not unique to neural networks. For example, automatically defined
functions (ADF) in genetic programming seem to serve similar
functions as hidden layers. But neural networks can learn via 
backpropagation and stochastic gradient descent, which seem more effective
than other methods e.g. crossover and mutation (which I believe is a kind of beam search)
of abstract syntax trees in genetic programming.

I am particularly interested in recurrent neural netorks. Long short-term memory networks (LSTMs)
and the [Neural Turing Machine][NTM] are two of them.
These two can "reprogram" themselves, either by activating/deactivating
different parts using gates (in the former), or by focusing its attention on
different parts (in the latter).

# TODO Think about/Read further:

  Reinforcement Learning

  Neural Programmer-Interpreters

    http://arxiv.org/abs/1511.06279

[blum]: https://www.cs.cmu.edu/~mblum/search/consc_d.pdf
[NTM]: https://github.com/yeoedward/Neural-Turing-Machine
