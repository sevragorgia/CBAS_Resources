![CBAS](https://github.com/sevragorgia/CBAS_Pictures/blob/master/Aquarium/CBAS_Bleached_vs_Aquarium_20-10-14.jpg)

![](https://github.com/sevragorgia/CBAS_Pictures/blob/master/Aquarium/CBAS_Bleached_vs_Aquarium_20-10-14.jpg&s=200)

# CBAS Resources

This is an umbrella site that hosts the data we generate on ***Lendenfeldia chondrodes***. It contains pointers to other repositories with data on this system.

Note that these other repositories are mantained independently and that this repository uses git **submodules** to pull those repositories and the most recent changes pushed to them. This repository **should not be used to introduce changes to the submodules**, it was only created to centralize all the data generated on *L. chondrodes*. If you want to contribute to one of the repositories, please send a pull request to that repository. The reason why I chose to provide this umbrella repository reflects the way in which the project develops. I think it is easier to develop independent repositories for specific projects and add these repos as submodules to this repository once the specific experiments are concluded, the data is available and is hopefully analyzed in some meaningful way.

The goal of this repository is thus to provide users with one single central hub that can be easily cloned with all the available information generated on *L. chondrodes* at a certain point in time. I hope this makes sense, and it makes your lives easier.

cheers

Sergio


## Cloning instructions

Copy the url using the clone button on the main page of this repository and open a new terminal. If you want git to fetch and update all the submodules on cloning, you need to pass the *--recursive* flag to *git clone*. Otherwise you need to use the *git submodule init* followed by *git submodule update* commands to get the data stored in the submodule repositories.


# About *L. chondrodes* 

*L. chondrodes* is a blue/purple/green encrusting sponge that can be commonly found in marine aquaria all over the world. *L. chondrodes* mantains a symbiotic relation with cyanobacteria of the Candidatus *Synechococcus spongiarum* group. In addition, other bacteria (at least 6 more) are present in its microbiome. The main objective of my research is to understand how this holobiont works. For this I mostly use *omic* methods (i.e. transcriptomics, (meta)genomics, etc). I think *L. chondrodes* represents a unique model sponge holobiont that can be easily investigated in different parts of the world.


## Experimental settings and detailed protocols used for different experiments

Another reason why I consider important to mantain this centralized repository is to keep somewhere a detailed as possible account on the experimental settings we use in our experiments. I have been trying to keep this as transparent as possible, but think that often more detail is necessary. The same happens with the protocols we use. I have optimized most of the through rounds of trial and error and too often journals do not accept long descriptions of procedures. 

# Current submodules

 - CBAS_DE: data and scripts used 1. assemble *L. chondrodes* reference transcriptome and 2. to assess gene expression changes during photo symbiont loss
 - CBAS_16S: 16S V4 amplicon data. This repo groups different projects, including our shading/bleaching experiment.
 - CBAS_Metagenome: metagenomic data including very preliminary bacterial assemblies. Note that these assemblies are very preliminar and will be superseeded by new high-quality ones (hopefully) in the near future.
 - CBAS_Pictures: a repo to keep together the original versions of the micro and macro pictures we take for different experiments.

## Planned future submodules

 - CBAS_Nanopore: a repo to summarize our results on the use of Nanopore sequencing on this system.
 - CBAS_Skin: a repo to summarize on going experiments on the microbiome associate with the "skin" of *L. chondrodes*

# What does CBAS means and why do I keep finding it.

The story goes:

by the time I started working with *L. chondrodes* its taxonomy was not clear. The only information I had about the sponge was:

 - it was blue
 - it can be found in many aquaria
 - in these systems is pretty common
 - is a sponge

from this information I came up with the acronym **C**ommon **Blue** **A**quarium **S**ponge (**CBAS**). I think this is nicer than *Lendenfeldia chondrodes* and will keep using it for my research.



