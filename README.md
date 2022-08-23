# OckhamsGuillotine

This repository contains a series of contests (the first of which is at [LaboratoryOfTheCounties](https://github.com/jabowery/OckhamsGuillotine/tree/master/LaboratoryOfTheCounties)) to create the best unified model of society by compressing a wide range of social data.  Compression discovers causal laws by approximating the underlying Kolmogorov Complexity of the data.  This is inspired by <a href="http://prize.hutter1.net/">the Hutter Prize for Lossless Compression of Human Knowledge</a>

See the Nature video "<a href="https://www.youtube.com/watch?v=rkmz7DAA-t8">Remodelling machine learning:  An AI that thinks like a scientist</a>" and its cited Nature journal article "<a href="https://www.nature.com/articles/s42256-018-0005-0">Causal deconvolution by algorithmic generative models</a>".

## Background

There are a number of *statistical* [model selection criteria](https://en.wikipedia.org/wiki/Model_selection#Criteria) that attempt to walk the tightrope between "overfitting" and "confirmation bias". Overfitting loses predictive power by simply memorizing the data without generalizing.  Confirmation bias loses predictive power by throwing out data that doesn't fit the model -- data that may point to a more predictive model.  Model selection criteria are generally called "information criteria", e.g. BIC is "Bayesan Information Criterion", AIC is "Akaike Information Criterion", etc. What they all have in common, is the *statistical* nature of their *information*.  That is to say, they are all based, directly or indirectly, on Shannon Information Theory.

Here's the critical difference in a nutshell:

Shannon Information regards the first billion bits of the number Pi to be random.  That is to say, there is no description of those bits in terms of Shannon Information that is shorter than a billion bits.

Algorithmic Information regards the first billion bits of the number Pi to be the shortest algorithm that outputs that precise sequence of bits.

Now, which of these two theories of "information" would you trust to predict the next bit of Pi?

Data-driven science frequently starts with statistical notions of information but in order to make predictions about the real world, they eventually take the form of algorithms that simulate world's dynamics.  This can sometimes be obscured by the introduction of complex numbers to mathematical models of the world, but ask any physicist what complex numbers "mean" in mathematical models of physics and they'll say "dynamics" which is a fancy word for "time".  However, when push comes to shove and the physicist is required to make a prediction of a real system, such as the weather, he'll admit that the only way to generate the prediction is to use the complex numbers to simulate the evolution of the real world in time by step-wise *algorithms*.
