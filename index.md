
![](CBAS.jpg)

# CBAS Resources

This is an umbrella site that hosts the data we generate on **CBAS***. It contains pointers to other repositories with data on this system.

Note that these other repositories are mantained independently and that this repository uses git **submodules** to pull those repositories and the most recent changes pushed to them. This repository **should not be used to introduce changes to the submodules**, it was only created to centralize all the data generated on **CBAS**. If you want to contribute to one of the repositories, please send a pull request to that repository. The reason why I chose to provide this umbrella repository reflects the way in which the project develops. I think it is easier to develop independent repositories for specific projects and add these repos as submodules to this repository once the specific experiments are concluded, the data is available and is hopefully analyzed in some meaningful way.

The goal of this repository is thus to provide users with one single central hub that can be easily cloned with all the available information generated on **CBAS** at a certain point in time. I hope this makes sense, and it makes your lives easier.

cheers

Sergio

***

# Cloning instructions

Copy the url using the clone button on the main page of this repository and open a new terminal. If you want git to fetch and update all the submodules on cloning, you need to pass the *--recursive* flag to *git clone*. Otherwise you need to use the *git submodule init* followed by *git submodule update* commands to get the data stored in the submodule repositories.

## Current submodules

 - [CBAS_DE][https://github.com/sevragorgia/CBAS_DE]: data and scripts used 1. assemble **CBAS** reference transcriptome and 2. to assess gene expression changes during photo symbiont loss.
 - [CBAS_16S][https://github.com/sevragorgia/CBAS_16S]: 16S V4 amplicon data. This repo groups data from different projects using 16S V4 amplicon sequencing. It includes our shading/bleaching experiment.
 - [CBAS_Metagenome][https://github.com/sevragorgia/CBAS_Metagenome]: metagenomic data including very preliminary bacterial assemblies. **Note** that these assemblies are very preliminar and will be superseded by new high-quality ones in the (hopefully near) future.
 - [CBAS_Pictures][https://github.com/sevragorgia/CBAS_Pictures]: a repo to keep together the original versions of the micro and macro pictures we take for different experiments.

## Planned future submodules

 - CBAS_Nanopore: a repo to summarize our results on the use of Nanopore sequencing on this system.
 - CBAS_Skin: a repo to summarize ongoing experiments on the microbiome associate with the "skin" of **CBAS**.
 - CBAS_Regeneration: a repo with data about tissue regeneration/growth in **CBAS**.

## Experimental settings and detailed protocols used for different experiments

Another reason why I consider important to mantain this centralized repository is to keep somewhere a detailed as possible account on the experimental settings we use in our experiments. I have been trying to keep this as transparent as possible, but think that often more detail is necessary. The same happens with the protocols we use. I have optimized most of the through rounds of trial and error and too often journals do not accept long descriptions of procedures. 

***

# About **CBAS** 

**CBAS** is a blue/purple/green encrusting sponge that can be commonly found in marine aquaria all over the world. **CBAS** mantains a symbiotic relation with cyanobacteria of the Candidatus *Synechococcus spongiarum* group. In addition, other bacteria (at least 6 more) are present in its microbiome. The main objective of my research is to understand how this holobiont works. For this I mostly use *omic* methods (i.e. transcriptomics, (meta)genomics, etc). I think **CBAS** represents a unique model  system for the study of sponge-microbiome interactions because it can be easily investigated in different parts of the world.

## What does CBAS means and why do I keep finding it.

The story goes:

by the time I started working with **CBAS** its taxonomy was not clear. The only information I had about the sponge was:

 - it was blue
 - it can be found in many aquaria
 - in these systems is pretty common
 - is a sponge

from this information I came up with the acronym **C**ommon **Blue** **A**quarium **S**ponge (**CBAS**). I think this is a nice name and will keep using it for my research.



