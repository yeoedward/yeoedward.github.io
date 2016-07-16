---
layout: post
title:  "Consciousness"
date:   2016-05-18
---

The part of Artificial intelligence I find most interesting is not so much the solving of 
problems intelligently, but rather computers having "a mind".

A natural first question in this line of inquiry, is whether or not it is
even possible for computers to think like humans. After all, computers
are pre-programmed and just mindlessly follow instructions.
But this is actually
the case for humans too. Our thoughts are
just neurons firing in a certain way. These neurons are governed by the laws
of physics. There is nothing to suggest that the human brain is more special (physically)
than an ant brain, or even weather patterns. In this sense, we too are mindlessly
obeying the laws of physics in our thoughts and actions.

So what, then, should the definition of consciousness
be? Something about the human brain makes it more interesting than the brain of an ant.
Sure, it is physically different, but the exciting part is the instructions that
both are "mindlessly" following. It was only lately, after taking a class on
[computability][flac], that
I have been exposed to the language and framework to think about this more precisely.
After all, computability can be thought of as the study of mindlessly following instructions.

The experience of free will seems like a paradox if we accept that we do not have it.
I believe this is resolved by [diagonalization][diag], in particular, [Rice's theorem][rice],
which I (very) loosely paraphrase as stating that it is impossible for a process capable
of self-reference to know how it is going to behave, because if it does know, it can decide
to behave differently. This trivial-sounding idea reminds me of a game that kids play, which 
is surprising because a lot of the computability proofs use similar arguments.
But anyway, I believe it is this that gives us the illusion of free will.
It seems others have had [similar thoughts][turing_free_will]!

I really like Manuel
Blum's initial attempts at [formalizing][conscs] consciousness, especially
his discussion of what good [definitions][blum] should look like. 

Perhaps [Deep Learning]({% post_url 2016-04-02-deep-learning %}), which concerns
itself with representation learning, can provide some insight into consciousness,
which can be thought of as the existence of some kind of internal self-representation. I am hoping
that putting neural networks in interesting (in a game theoretic sense) situations
will result in them acquiring internal models of the self and the
environment.

Consciousness means many things. None of them are special. "Soul" is an illusion. Instead, what is uniquely human is resourcefulness?

# To read/think:

  The Society of Mind.

  The Emotion Machine.

  Automating Turing reductions? Changing between problem representations, like in Minsky's frames.

  Chaitin and [algorithmic information theory][chaitin].


[flac]: http://www.cs.cmu.edu/~flac/
[diag]: https://en.wikipedia.org/wiki/Diagonal_lemma
[rice]: https://en.wikipedia.org/wiki/Rice%27s_theorem
[turing_free_will]: http://arxiv.org/abs/1310.3225
[blum]: https://www.cs.cmu.edu/~mblum/research/pdf/cons.html
[conscs]: https://www.cs.cmu.edu/~mblum/search/consc_d.pdf
[chaitin]: https://en.wikipedia.org/wiki/Algorithmic_information_theory
