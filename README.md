# OckhamsGuillotine

CAVEAT:  Ockham's Guillotine promotes a specific criterion for model *selection*.  It does not constrain how those models are *generated*.  Models *generated* by a million monkies banging keyboards for a billion years are permitted as well as those by machine learning algorithms or by graduate students laboriously slaving for their PhDs.  None of that is relevant.  Ockham's Guillotine is *only* about model *selection*.

This repository contains a series of contests (the first of which is at [LaboratoryOfTheCounties](https://github.com/jabowery/OckhamsGuillotine/tree/master/LaboratoryOfTheCounties)) to create the best unified model of social causation.  By Ockham's Razor, the smallest *[executable archive](https://en.wikipedia.org/wiki/Self-extracting_archive)* of a wide range of social data represents the best model of social causation one can produce *given* that social data.  This is inspired by <a href="http://prize.hutter1.net/">the Hutter Prize for Lossless Compression of Human Knowledge</a>

See the Nature video "<a href="https://www.youtube.com/watch?v=rkmz7DAA-t8">Remodelling machine learning:  An AI that thinks like a scientist</a>" and its cited Nature journal article "<a href="https://www.nature.com/articles/s42256-018-0005-0">Causal deconvolution by algorithmic generative models</a>".

## Background

There are a number of *statistical* [model selection criteria](https://en.wikipedia.org/wiki/Model_selection#Criteria) that attempt to walk the tightrope between "overfitting" and "confirmation bias". Overfitting loses predictive power by simply memorizing the data without generalizing.  Confirmation bias loses predictive power by throwing out data that doesn't fit the model -- data that may point to a more predictive model.  Model selection criteria are generally called "information criteria", e.g. BIC is "Bayesan Information Criterion", AIC is "Akaike Information Criterion", etc. What they all have in common, is the *statistical* nature of their *information*.  That is to say, they are all based, directly or indirectly, on Shannon Information Theory.

Here's the critical difference in a nutshell:

Shannon Information regards the first billion bits of the number Pi to be random.  That is to say, there is no description of those bits in terms of Shannon Information that is shorter than a billion bits.

Algorithmic Information regards the first billion bits of the number Pi to be the shortest algorithm that outputs that precise sequence of bits.

Now, which of these two theories of "information" would you trust to predict the next bit of Pi?

Data-driven science frequently starts with statistical notions of information but in order to make predictions about the real world, they eventually take the form of algorithms that simulate the causal structures of the world being modeled.  It is at this transition from Shannon Information to Algorithmic Information that causation *necessarily* enters the model and does so based on the assumption of any natural science:  That reality is structured in such a way that we can use arithmetic to predict future observations based on past observations.
