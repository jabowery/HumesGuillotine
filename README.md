# HumesGuillotine

**cynic**: A blackguard whose faulty vision sees things as they are, not as they ought to be.\
-- Ambrose Bierce's *Devil's Dictionary*

It's way past time to get ruthless about understanding the causal structure of macrosocial dynamics.

This repository is a series of competitions toward rigorous ethics* in AGI founded on [Hume's Guillotine](https://youtu.be/UwkSA8nqmdI):  Separating the question of what _IS_ from what _OUGHT_ to be the case.  These competitions focus on what _IS_ the case, not on what _OUGHT_ to be the case.  Science discovers what _IS_ the case, not what _OUGHT_ to be the case.  These competitions advance the scientific method with Algorithmic Information Theory which permits us to discover what causes what _even in the absence of experimental controls_.  Vital and complex fields such as sociology, especially macrosociology, rely on "natural experiments" conducted without adequate experimental controls to determine causality.  Conflicts, even bloodshed, usually arise over differing theories (beliefs) about social causation.  This is true even when we share the same value systems which are ideas of what _OUGHT_ to be the case. Technological civilization's increasing interconnectedness makes it increasingly brittle hence intolerant of such conflicts.  Leaving conflict resolution up to ill-informed decision-makers is a recipe for global disaster.  Hume's Guillotine contests can offer vital information to decision-makers who are now ill-informed.

These contests also bear directly on the foundation of Artificial General Intelligence.  In Marcus Hutter's rigorous top down AGI theory, AIXI, Algorithmic Information Theory provides the _IS_ and Sequential Decision Theory provides the _OUGHT_.  Another way of stating that is Algorithmic Information Theory provides what _IS_ the case in the form of scientific knowledge.  Sequential Decision Theory provides what _OUGHT_ to be the case in the form of engineering: Scientific knowledge applied by decision-makers.

Out of all so-called "Information Criteria" for model selection, the Algorithmic Information Criterion is the best we can do in scientific discovery of causality _**relative to** a given set of observations_.  ["Many analysts, one dataset"](https://www.socialjudgments.com/docs/Silberzahn_Uhlmann_Martin_et_al_in_press_Many_Analysts.pdf), the current best practice in meta-scientific research hence scientific ethics, is one step shy of the Algorithmic Information Criterion for causal model selection. That step?  Understand that the best analysts will be able to _losslessly compress_ the "one dataset" best.  This is how you make competition fair, objective and optimal between schools of thought.  This has actually been [in the published literature since 1964](https://en.wikipedia.org/wiki/Solomonoff%27s_theory_of_inductive_inference) but has been ignored despite its direct relevance to the half century of exponential growth in computation and data analysis.  This is largely because _statistical_ methods were developed in the age before computers.  The idea that one should develop algorithms that simulate the real world's complex feed-back _dynamics_ between a wide range of longitudinal social measures was simply inconceivable.  But the real world isn't _static_ nor composed of disconnected systems that have a single dependent variable like "crime" or "poverty".  Statistics aren't the right way to proceed.  Dynamics _are_ the right way to proceed, and dynamics are irreducibly complicated.  Failing to face the hard problem of dynamics is why no one can agree on anything and why motivated reasoning continually rears its ugly head in sociology.  This leads, ultimately, to political conflict.  Much of it is unnecessary conflict.

How AIT works is the essence of simplicity known as Ockham's Razor:  Pick your data however you like, and find the smallest algorithm that generates all of that data -- leaving _nothing_ out: Not even what you consider "noise" or "errors in measurement".  This is lossless compression of your data.  The reason you keep all "errors in measurement" -- the reason you avoid lossy compression -- is to avoid what is known as "confirmation bias" or, what might be called "Ockham's Chainsaw Massacre".  Almost all criticisms of Ockham's Razor boil down to mischaracterizing it as Ockham's Chainsaw Massacre.  The remaining criticisms of Ockham's Razor boil down to the claim that those selecting the data never include data that doesn't fit their preconceptions.  That critique _may_ be reasonable but it is not an argument against the Algorithmic Information Criterion, which only applies to a _given_ dataset.  Models and data are different.  Therefore model selection criteria are qualitatively different from data selection criteria.

Yes, people can _and will_ argue over what data to include or exclude -- but the Algorithmic Information Criterion traps the intellectually dishonest by making their job much harder since they must include _exponentially_ much more data that is biased towards their particular agenda in order to wash out data coherence (and interdisciplinary consilience) in the rest of the dataset.  The ever-increasing diversity of data sources _identifies_ the sources of bias -- and then starts predicting the behavior of data sources in terms of their bias, _as_ bias.  Trap sprung!  This is much the same argument as that leveled against conspiracy theories:  At some point it becomes simply impractical to hide a lie against the increasing diversity of observations and perspectives.

Hume's Guillotine is concerned *only* with discovering what *IS* the case via the Algorithmic Information Criterion for causal model _selection_.  _**Objective** scoring_ of a scientific model by the Algorithmic Information Criterion is _utterly **independent_** of how the model was created.  In this respect, Hume's Guillotine doesn't even care whether computers were used to create the model, let alone which machine learning algorithms might be used.

This repository contains a series of datasets (the first of which is at [LaboratoryOfTheCounties](https://github.com/jabowery/HumesGuillotine/tree/master/LaboratoryOfTheCounties)) to create the best unified model of social causation.

See the Nature video "<a href="https://www.youtube.com/watch?v=rkmz7DAA-t8">Remodelling machine learning:  An AI that thinks like a scientist</a>" and its cited Nature journal article "<a href="https://www.nature.com/articles/s42256-018-0005-0">Causal deconvolution by algorithmic generative models</a>".

\* Rigor in ethics applies _intrinsic values_ in deciding what _OUGHT_ to be done subject to what _IS_.  Sequential Decision Theory is, in this respect, AGI's rigorous ethical reasoning.  SDT depends on Algorithmic Information Theory for what _IS_, and on its _given_ utility function for its _intrinsic values_.  Failure to recognize this has intellectually crippled the field of AGI ethics.

## Background

There are a number of *statistical* [model selection criteria](https://en.wikipedia.org/wiki/Model_selection#Criteria) that attempt to walk the tightrope between "overfitting" and "confirmation bias". Overfitting loses predictive power by simply memorizing the data without generalizing.  Confirmation bias loses predictive power by throwing out data that doesn't fit the model -- data that may point to a more predictive model.  Model selection criteria are generally called "information criteria", e.g. BIC is "Bayesian Information Criterion", AIC is "Akaike Information Criterion", etc. What they all have in common, is the *statistical* nature of their *information*.  That is to say, they are all based, directly or indirectly, on Shannon Information Theory.

Here's the critical difference in a nutshell:

Shannon Information regards the first billion bits of the number Pi to be random.  That is to say, there is no description of those bits in terms of Shannon Information that is shorter than a billion bits.

Algorithmic Information regards the first billion bits of the number Pi to be the shortest algorithm that outputs that precise sequence of bits.

Now, which of these two theories of "information" would you trust to predict the next bit of Pi?

The analogy to natural science works.  Consider the following data in the context of Shannon Information Theory and then in the context of Algorithmic Information Theory:

Time series positions of 3 celestial bodies in mutual orbit.

It is obvious how Algorithmic Information Theory treats that data but how do you "encode" the dynamics of that system with statistics?

A number theorist will choose some data (e.g. digits of pi) and a sociologist will choose another dataset (e.g. the General Social Survey), but the only way to capture the causal structure's dynamics is with an algorithm.

Data-driven science frequently starts with statistical notions of information but in order to make predictions about the real world, they eventually take the form of algorithms that simulate the causal structures of the world being modeled.  It is at this transition from Shannon Information to Algorithmic Information that causation *necessarily* enters the model and does so based on the assumption of any natural science, i.e.:  

**That reality is structured in such a way that we can use arithmetic to predict future observations based on past observations.**
