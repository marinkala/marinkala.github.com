---
layout: default
title: Projects
excerpt: "This is my landing page"
permalink: /projects/
---

# Graduate Projects

## Twitter Information Diffusion and Cooperation
I have been working on various aspects of information diffusion on Twitter in the context of natural disaster. 
Our [CSCW paper](https://www.cs.colorado.edu/~palen/palen_papers/CSCW-SandyRetweetPaperCR.pdf) on the retweet patterns of geo-vulnerable Twitter users during 2012 Hurricane Sandy, investigates whether they spread information differently, including what and whose content they chose to propagate. We investigate whether the Twitter-based relationships are preexisting or if they are newly formed because of the disaster, and if so if they persist. We find that the people in the path of the disaster favor in their retweeting locally-created tweets and those with locally-actionable information. They also form denser networks of information propagation during disaster than before or after.
Currently, I am investigating the conversational activity that takes place through the @mention convention in disaster.

## Protective Decision-making on Social Media in Crisis
I am currently working in collaboration with the National Center for Atmospheric Research (NCAR) on project [CHIME](https://www.mmm.ucar.edu/communicating-hazard-information-modern-environment-chime), in which we are investigating “protective decision-making” practices of Twitterers active during coastal hazards, such as 2012 Hurricane Sandy.

## Analytics for OpenStreetMap History Data
We are developing epic-osm: A software framework for OpenStreetMap full-history analysis.
We have built a framework on Ruby and MongoDB with a static Jekyll and Javascript front-end which enables analysis of OSM history files.

[epic-osm website](http://project-epic.github.io/epic-osm/)

## Work Practices and Cooperation in OpenStreetMap
In this project, we explore the work practices and interactions of volunteer mappers operating in the high-tempo, high-volume context of disasters. We focus on the digital volunteer work in OpenStreetMap (OSM) in response to the 2010 Haiti earthquake - an early crisis mapping effort before the community norms chrystalized and technical intreventions reshaped distributed mapping practices. To do this, we built upon and expanded prior network analysis techniques to select high-value portions of the vast OSM data for further qualitative analysis. We then performed detailed content analysis of the identified activity and, where possible, conducted interviews with the participants. This research allowed the identification of seven distinct mapping practices that can be classified according to dimensions of time, space, and interpersonal interaction.  After the salient work practices were identified, we used network motifs to further refine our methods, so they can more easily isolate the practices. Our work represents a baseline for future research about how OSM crisis mapping practices have evolved over time.

![Filling In the Map](/assets/fillInMap.png)

## Sports dynamics
We investigated the time evolution of lead changes within individual games of competitive team sports. Exploiting ideas from the theory of random walks, the number of lead changes within a single game follows a Gaussian distribution. We show that the probability that the last lead change and the time of the largest lead size are governed by the same arcsine law, a bimodal distribution that diverges at the start and at the end of the game. We also determine the probability that a given lead is “safe” as a function of its size L and game time t. Our predictions generally agree with comprehensive data on more than 1.25 million scoring events in roughly 40 000 games across four professional or semiprofessional team sports, and are more accurate than popular heuristics currently used in sports analytics. This work has been published in [Physical Review E](http://journals.aps.org/pre/abstract/10.1103/PhysRevE.91.062815) and has been publicized in [Slate](http://www.slate.com/articles/sports/sports_nut/2015/06/golden_state_warriors_championship_a_new_formula_for_predicting_lead_changes.html) and [New Scientist](https://www.newscientist.com/article/dn27836-winning-formula-reveals-if-your-team-is-too-far-ahead-to-lose).

![LastLeadChange](/assets/LastLeadChange.jpg)

## Measuring Segregation based on Neighborhood Social Interactions 
We used spectral methods to measure housing segregation at both the individual and community (neighborhood) level in 1880 Baltimore, while making use of the geographic and social structure in the population. Classic measures of segregation depend on the spatial resolution and they also do not account for any structure in the population, ignoring social relationships. Using Spectral Segmenation Index on the neighboir network allows us to overcome the level of granulatity problem and make use of the inferred social relationships.

![SSI](/assets/SSI.png)

# Undergraduate Projects

## Creating Background Sets for LSI Classification
We developed a method for mining the web to improve text classification,by creating a background text set. Our algorithm
used the information gain criterion to create lists of importantwords for each class of a text categorization problem. It then
searched the web on various combinations of these words to produce a set of related data. We used this set of background text with Latent Semantic Indexing classification to create an expanded term by document matrix on which singular value
decomposition was done. This work has been published at [FLAIRS](https://www.aaai.org/Papers/FLAIRS/2006/Flairs06-117.pdf).

## Protein Folding
I worked on an automated tool for detecting critical events in the folding landscape of proteins. We developed a new method that can detect critical events such as bends and loops and compare among different trajectories of a simple protein model of 60 beads. This work was supported by the CRA-W Distributed Mentor Project.

<!-- ![contactMap](/assets/contactMap.png) -->

## Spiking Neurons
We constructed neural network simulations of the basic olfactory brain dynamics. The various neural network architectures consisted of 3-4 layers of Spiking neurons. The biological parameters, such as synapse weights and time delays, remained constant from simulation to simulation, making the variations in the resulting membrane potential solely the function of the network architecture.

![spiking](/assets/spiking.jpg)