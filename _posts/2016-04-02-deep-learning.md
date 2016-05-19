---
layout: post
title:  "Deep Learning"
date:   2016-05-18
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
functions (ADF) in genetic programming seems to serve a similar
function as hidden layers. But neural networks can learn via 
backpropagation and stochastic gradient descent, which seems more effective
than crossover and mutation (which I believe is a kind of beam search) of
program syntax trees in genetic programming.

Why am I using genetic programming as a point of comparsion? I am primarily
interested in [consciousness]({% post_url 2016-03-30-consc %}), which 
I believe has the property of universality, which I previously considered
to be the same as Turing-completeness. Enter genetic programming.
But Manuel Blum's definition
of what it means to be universal in [CONSCS][blum] is better:

>  Most importantly, the entity is universal:
roughly, its learning algorithms are sufficiently powerful to enable it to acquire
any model that can be acquired by a general-purpose CONSCS. 

So Turing-completeness does not seem like the right property here, although
it is somewhat analogous.

For the same reasons, I am particularly interested in recurrent
neural netorks, because it seems having a concept of self should require
the capability of storing state. Long short-term memory networks (LSTMs)
and the Neural Turing Machine are particularly interesting recurrent networks.
They allow the network to reprogram itself, either by activating/deactivating
different parts using gates (in the former), or by focusing its attention on
different parts (in the latter).

# TODO Think about/Read further:

  Reinforcement Learning

  Neural Programmer-Interpreters

    http://arxiv.org/abs/1511.06279

[blum]: https://www.cs.cmu.edu/~mblum/search/consc_d.pdf
