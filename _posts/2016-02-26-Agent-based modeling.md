---
layout: post
title: Agent-Based Modeling
subtype: Research
---

### Overview

Agent-based modeling is a computational approach that simulates the emergent outcomes that arise from the unique behaviors of autonomous 
individuals and their interactions with one another. This type of modelling is a powerful tool for representing discrete stochastic biological processes,
such as cells interacting with each other and responding to environmental cues within a tissue.

### Muscle Atrophy

<iframe width="480" align="middle" height="360" src="https://www.youtube.com/embed/oXthci6ar5s?rel=0&amp;controls=0&amp;showinfo=0&autoplay=1" frameborder="0"></iframe>
<br>
Disuse-induced mucle atrophy is a common medical complication that can result from prolonged bedrest or inactivity. I constructed an agent-based model to study
muscle specific differences in susceptibility to disuse. The model, which is shown in the movie above, is a muscle fascicle undergoing [disuse-induced](https://simtk.org/home/muscle_abm) atrophy. 
After parameterizing the model to rat studies, I simulated atrophy rates across limb muscles in the rat (such as the forelimb and hindlimb muscles in the graph below). 
I also simulated fibroblasts and their secretions, pointing to a potential source of TNF-alpha that can alter the rate of atrophy during disuse.

<p><img src="/images/ABM_atrophy_flexors.png"></p> 


### Muscle Injury and Inflammation

<iframe width="480" align="middle" height="360" src="https://www.youtube.com/embed/sJIq7gGsWjE?rel=0&amp;controls=0&amp;showinfo=0&autoplay=1" frameborder="0"></iframe>
<br>

<p style="float: right;"><img class="margined" width="340px" src="/images/ABM_inflammation_macKO.png"></p> 

Muscles can be injured in many different ways, from contusions and lacerations to hypoxia and toxins. 
In all of these cases, healthy muscle recovery requires the temporal and spacial coordination of numerous cell types (muscle fibers, satellite stem cells, neutrophils, macrophages, fibroblasts, etc).
In order to study these cellular interactions, I expanded my agent-based model to include inflammation and regeneration following injury. 
In the video of my muscle injury model (above), you can see the onset of an injury (damaged muscle turns blue) followed by inflammation and the initiation of regeneration. 
I used a genetic algorithm to tune the behaviors of neutrophils, M1 and M2 macrophages during muscle injury to emulate *in vivo* data.
Once tuned, simulations of macrophage knockdown following injury (right) showed impaired muscle recovery and prolonged necrotic tissue, consistent with numerous published studies.

<div style="clear:right">