---
layout: post
title: Stability criteria in Nature
type: post
categories: Papers
tags: [papers]
---

Back in 2001, when I was studying for my PhD entrance exam, I read May's 1972 paper for the first time, and fell in love with this problem.

May's result is very simple to explain: take _S_ species and suppose that each species interacts with any other with probability _C_. Then, the expected number of connections for each species is _SC_. Now assume that the ecosystem is at a steady state: species do not change in density through time if not perturbed. If two species interact, the effect of species _a_ on species _b_ is taken from a normal distribution with mean _0_ and variance _σ²_. Finally, the effect of _a_ species on itself is assumed to be _-1_ (i.e., there is some sort of self-regulation).

May showed that such networks are almost surely stable (i.e., persist in time despite small perturbations) whenever _σ√SC_\<1, while whenever this threshold is crossed the system is almost surely unstable, and thus should not persist through time. This result sparked a fierce "complexity-stability" debated that lasts to this day. In fact, May's results are difficult to reconcile with the staggering diversity observed in nature: many species (large _S_) interact in complex networks (large _C_) of ecological interactions, despite mathematical considerations would tell us this is not possible.

Si and I tackled this problem in a new article just published by Nature:

**_Stability criteria for complex ecosystems_**

_Forty years ago, May proved that sufficiently large or complex ecological networks have a probability of persisting that is close to zero, contrary to previous expectations. May analysed large networks in which species interact at random. However, in natural systems pairs of species have well-defined interactions (for example predator–prey, mutualistic or competitive). Here we extend May’s results to these relationships and find remarkable differences between predator–prey interactions, which are stabilizing, and mutualistic and competitive interactions, which are destabilizing. We provide analytic stability criteria for all cases. We use the criteria to prove that, counterintuitively, the probability of stability for predator–prey networks decreases when a realistic food web structure is imposed or if there is a large preponderance of weak interactions. Similarly, stability is negatively affected by nestedness in bipartite mutualistic networks. These results are found by separating the contribution of network structure and interaction strengths to stability. Stable predator–prey networks can be arbitrarily large and complex, provided that predator–prey pairs are tightly coupled. The stability criteria are widely applicable, because they hold for any system of differential equations._

