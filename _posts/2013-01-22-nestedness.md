---
layout: post
title: Nestedness
date: 2013-01-22 19:23:46.000000000 -06:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Code
- Papers
tags: []
meta:
  _edit_last: '1'
author:
  login: siteadmin
  email: sallesina@uchicago.edu
  display_name: siteadmin
  first_name: ''
  last_name: ''
permalink: "/"
---
I always joke in the lab that anybody who wants to propose a new measure in ecology (or index, etc.) should pay $1,000, $2,000 if the new measure has an acronym. These funds could pay for graduate students to go to some conference.

The only exception to the rule is for studies showing that two seemingly different measures are in fact the same thing. This is the case of our recent study on nestedness, published today in Nature Communications:

The ghost of nestedness in ecological networks  
Phillip P. A. Staniczenko, Jason C. Kopp & Stefano Allesina  
_Ecologists are fascinated by the prevalence of nestedness in biogeographic and community data, where it is thought to promote biodiversity in mutualistic systems. Traditionally, nestedness has been treated in a binary sense: species and their interactions are either present or absent, neglecting information on abundances and interaction frequencies. Extending nestedness to quantitative data facilitates the study of species preferences, and we propose a new detection method that follows from a basic property of bipartite networks: large dominant eigenvalues are associated with highly nested configurations. We show that complex ecological networks are binary nested, but quantitative preferences are non-nested, indicating limited consumer overlap of favoured resources. The spectral graph approach provides a formal link to local dynamical stability analysis, where we demonstrate that nested mutualistic structures are minimally stable. We conclude that, within the binary constraint of interaction plausibility, species preferences are partitioned to avoid competition, thereby benefiting system-wide resource allocation._

We uploaded the code needed for the analysis [here](http://allesinalab.uchicago.edu/wp-content/uploads/2014/05/GhostNestednessCode.zip).

