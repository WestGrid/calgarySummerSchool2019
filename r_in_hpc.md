---
layout: default
title: R in HPC Environment
nav: false
---

# R in HPC Environment

**Instructor**: Mark Lowerison (Community Health Sciences)

Using R and a variety of other technologies, I plan to demonstrate a multi-agent parameter search simulation project. We will be looking at differences in performance of two randomization strategies confounding mitigation in clinical trial settings.

The technical approach: 

1. Generate a simulation space/parameter set to be analyzed.
2. Write a simulation agent to consume parameter sets.

	a. This agent will fetch a parameter set.
	
	b. Generate a synthetic data set.
	
	c. Model this dataset and assess confounding between a key covariate and a treatment effect.
	
	d. Extract results from the R model output and push them back to a results store.
	
3. Write a minimal dashboard to monitor the simulation under way and summarize some results as they progress.
 

**Target audience**: Attendees will walk away with working code samples and understanding of how to leverage distributed computing infrastructure to support containerized development of multi-agent simulation projects in R (and friends).

<!-- **Course plan**: -->

**Duration**: 3 hours

**Level**: intermediate to expert

**Prerequisites**: In addition to R, this presentation will use a little bit of Python, Git, Docker, Singularity, bash and Slurm. This course assumes a basic familiarity with at least some of these tools. In particular, some previous experience with R (or DataFrames in pandas) would be extremely valuable.

**Laptop software**: All attendees will need to bring their laptops with wireless access and with a
remote SSH client installed (on Windows laptops we recommend <a href="https://mobaxterm.mobatek.net/download.html" target="_blank">the free edition</a>; on Mac and Linux
laptops no need to install anything for ssh). It will also be important for attendees to have Git and Docker installed on their laptops.  
